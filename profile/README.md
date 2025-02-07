# BioDT GitHub Organisation

The repositories here contain codes and material developed within [the BioDT project](https://biodt.eu/) funded by the European Union's Horizon Europe research and innovation programme under grant agreement [No 101057437](https://doi.org/10.3030/101057437). 

## Prototype Digital Twins (pDTs)

The pDTs have been developed within the BioDT use cases (UCs), and the codes are available in the corresponding repositories:

* [Honeybee pDT / Pollinators UC](https://github.com/BioDT/uc-pollinators)
* [Cultural Ecosystem Services pDT / UC](https://github.com/BioDT/uc-ces)
* [Crop Wild Relatives pDT / UC](https://github.com/BioDT/uc-cwr)
* [Forest Biodiversity pDT / UC](https://github.com/BioDT/uc-forest-bird)
* Invasive Alien Species pDT: [workflows](https://github.com/BioDT/uc-ias-workflows); [IASDT.R](https://github.com/BioDT/IASDT.R) package

## BioDT web application [app.biodt.eu](https://app.biodt.eu)

The codes for [the BioDT shiny web app](https://app.biodt.eu) are available [here](https://github.com/BioDT/biodt-shiny).

---

## Guidelines for naming new repositories

- Use lower-case letters where possible.
- General-use features identified by adding `general` to the beginning of the repository name, e.g. `general-datamover`.
- Use case-specific code similarly identified by `uc` and the name of the UC, e.g. `uc-grassland`.

Separate features (such as individual digital twin components) may be kept in folders inside a given repository. In case it is preferable to create a separate repository for a feature, the name of the feature should be added to the end of the repository name (e.g. `uc-grassland-feature1`).
