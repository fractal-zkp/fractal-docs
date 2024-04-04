# Data Availability

**External Data Availability Integration with Fractal**

Fractal offers a native data availability solution as an integral part of its infrastructure via the [fractal-hub-availability-and-finality-layer.md](../architecture/fractal-hub-availability-and-finality-layer.md "mention"). However, recognizing the diverse needs and preferences of different rollups, some may opt to utilize external data availability providers. To accommodate this flexibility, Fractal supports seamless integrations with third-party data availability providers, allowing rollups to choose a provider that best suits their requirements.

**Benefits of External Data Availability Integration:**

* Enhanced flexibility: Rollups can choose from a variety of data availability providers based on their specific needs, preferences, and regulatory requirements.
* Customizable solutions: Integration with third-party providers enables rollups to tailor their data availability solutions to suit their unique use cases and operational workflows.
* Increased reliability: Access to multiple data availability providers enhances redundancy and resilience, reducing the risk of single points of failure.

**Supported Integrations:**

| Provider | Status            |
| -------- | ----------------- |
| Celestia | Complete          |
| EigenDA  | Development phase |
| Avail    | Research phase    |
