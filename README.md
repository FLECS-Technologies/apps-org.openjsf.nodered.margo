# apps-org.openjsf.nodered.margo

# margo example app

This git repository is an example for a margo compliant app.

The application package has the following folder structure:

```yaml
/                            # REQUIRED top-level directory
└── margo.yaml               # REQUIRED application description file in YAML Format
└── resources                # OPTIONAL folder with application catalog resources e.g., icon, license file, release notes
```

The `margo.yaml` file is the application description. The purpose of this file is to present the application on an application catalog or marketplace from where an end user selects the application to hand it over to the Workload Orchestration Software, which configures it and makes it available for installation on the edge device (see Section [Workload Management Interface](https://specification.margo.org/orchestration/workload/workload-management-interface-breakdown/)).
