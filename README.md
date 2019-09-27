# ETL-Migrator
ETL implementation for traceability migrator

This project is the implementation for the traceability migrator that can be tested with the case study in this repository. This project basically contains the following executable transformations:

- /ETLMigrator/model/TraceabilityMigrator.etl is the migrator taking as input the two traceability models and giving in output the migrated one, generated in the gen folder.
- /ETLMigrator/model/generateModelink.egl and .egx are the code generator to re-generated the updated weaving models to inspect the trace links of the migrated trace model.
In order to execute and inspect the case study:

launch the ETLMigrator with the .launch file /ETLMigrator/TraceMigrator.launch
launch the generateModelink for generating the weaving representation using trace/ETLMigrator/generateModelinkForTrace.launch
When the execution is finished copy the generated /ETLMigrator/model/gen/T.modelink to the /TraceabilityModel/case-study/gen folder in order to see the weaving representation for the migrated /TraceabilityModel/case-study/gen/Company2CRM.model
