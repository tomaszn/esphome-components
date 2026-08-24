# ESPHome components for ESP8266 + CC1101

This is a fork of [SzczepanLeon's ESPHome components](https://github.com/SzczepanLeon/esphome-components).

It is intended for **ESP8266-based devices using CC1101** which are no longer supported by the current upstream project.

## Usage

Add this repository as an ESPHome external component:

```yaml
external_components:
  - source: github://tomaszn/esphome-components@version_3
    components: [wmbus]
```

Then configure the `wmbus` component as usual, as described in the original [Version 3 documentation](https://github.com/SzczepanLeon/esphome-components/tree/version_3).

## Credits

This project is based on the work of **SzczepanLeon** and the contributors to the original project.

* **Upstream:** https://github.com/SzczepanLeon/esphome-components
* **Original Version 3:** https://github.com/SzczepanLeon/esphome-components/tree/version_3
* **This fork:** https://github.com/tomaszn/esphome-components
* **ESPHome:** https://esphome.io/

Pull requests and improvements are welcome.
