# AssetRepresentationRulesets

This repository maintains the rulesets that converts general descriptions of building assets to building classes with associated attributes used for hurricane damage and loss assessment. These rulesets are initially developed for SimCenter testbeds for [Atlantic County, NJ](https://nheri-simcenter.github.io/R2D-Documentation/common/testbeds/atlantic_city/index.html) and [Lake Charles, LA](https://kuanshi.github.io/HurricaneTestbedDoc/common/testbeds/lake_charles/index.html). Details of these rulesets are available in two forms:

* Ruleset definition tables (PDFs), as a copy of the curation in DesignSafe that include detailed documentation justifying the rules and provenance information for sources engaged in the development.
* Python scripts that implement the ruleset logic.

The rulesets are arranged by states (e.g., NJ for New Jersey) and [pytest](https://docs.pytest.org/en/6.2.x/) scripts are also developed for verification. The current implementation is geared for two states (i.e., NJ and LA) and for [HAZUS](https://www.fema.gov/flood-maps/products-tools/hazus) type damage and loss assessment. Application, extension and development of rulesets are welcome and please reach out to us if you have any questions or comments.
