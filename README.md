# LGTM Minimal Chart

This is a minimal chart for testing LGTM (Loki, Grafana, Tempo, Mimir). It provides a basic setup to quickly get started with LGTM.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed:

- [Helm](https://helm.sh/)
- [Kubernetes](https://kubernetes.io/)

## Versions

- Grafana:
- Mimir:
- Loki:
- Tempo:

## Installation

To install the LGTM minimal chart, follow these steps:

1. Clone the repository:

    ```shell
    git clone https://github.com/grafana/helm-charts.git
    ```

2. Change to the `lgtm-minimal` directory:

    ```shell
    cd helm-charts/lgtm-minimal
    ```

3. Install the chart using Helm:

    ```shell
    helm install lgtm .
    ```

## Configuration

The LGTM minimal chart can be configured using the values.yaml file. You can customize various aspects of the chart, such as the number of replicas, resource limits, and more.

For detailed configuration options, refer to the [values.yaml](./values.yaml) file.

## Usage

Once the chart is installed, you can access the LGTM components using the following URLs:

- Loki: http://<LOKI_HOST>:<LOKI_PORT>
- Grafana: http://<GRAFANA_HOST>:<GRAFANA_PORT>
- Tempo: http://<TEMPO_HOST>:<TEMPO_PORT>
- Mimir: http://<MIMIR_HOST>:<MIMIR_PORT>

Replace `<LOKI_HOST>`, `<LOKI_PORT>`, `<GRAFANA_HOST>`, `<GRAFANA_PORT>`, `<TEMPO_HOST>`, `<TEMPO_PORT>`, `<MIMIR_HOST>`, and `<MIMIR_PORT>` with the appropriate values.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](./LICENSE).
