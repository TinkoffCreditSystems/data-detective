| urn                                              | loaded_by       | entity_name                   | entity_type   | entity_name_short   | info                                                                      | search_data                                                                    | codes   | grid   | json_data   | json_system                                                       | json_data_ui   | htmls   | links   | notifications   | tables   | tags   |
|:-------------------------------------------------|:----------------|:------------------------------|:--------------|:--------------------|:--------------------------------------------------------------------------|:-------------------------------------------------------------------------------|:--------|:-------|:------------|:------------------------------------------------------------------|:---------------|:--------|:--------|:----------------|:---------|:-------|
| urn:job:dd:airflow:dd_load_dds_dag               | dd_load_dds_dag | dd_load_dds_dag               | JOB           |                     | Loading meta information from dag in data detective                       | urn:job:dd:airflow:dd_load_dds_dag dd_load_dds_dag                             |         |        |             | {'type_for_search': 'Job', 'system_for_search': 'Data Detective'} |                |         |         |                 |          |        |
| urn:job:dd:airflow:dd_load_dds_pg                | dd_load_dds_dag | dd_load_dds_pg                | JOB           |                     | Loading meta information from postgres database                           | urn:job:dd:airflow:dd_load_dds_pg dd_load_dds_pg                               |         |        |             | {'type_for_search': 'Job', 'system_for_search': 'Data Detective'} |                |         |         |                 |          |        |
| urn:job:dd:airflow:dd_load_dds_root              | dd_load_dds_dag | dd_load_dds_root              | JOB           |                     | Loading root entities                                                     | urn:job:dd:airflow:dd_load_dds_root dd_load_dds_root                           |         |        |             | {'type_for_search': 'Job', 'system_for_search': 'Data Detective'} |                |         |         |                 |          |        |
| urn:job:dd:airflow:dd_load_tuning_breadcrumb     | dd_load_dds_dag | dd_load_tuning_breadcrumb     | JOB           |                     | Loading the breadcrumb of relations from root to entity                   | urn:job:dd:airflow:dd_load_tuning_breadcrumb dd_load_tuning_breadcrumb         |         |        |             | {'type_for_search': 'Job', 'system_for_search': 'Data Detective'} |                |         |         |                 |          |        |
| urn:job:dd:airflow:dd_load_tuning_relations_type | dd_load_dds_dag | dd_load_tuning_relations_type | JOB           |                     | Loading entity relationship types                                         | urn:job:dd:airflow:dd_load_tuning_relations_type dd_load_tuning_relations_type |         |        |             | {'type_for_search': 'Job', 'system_for_search': 'Data Detective'} |                |         |         |                 |          |        |
| urn:job:dd:airflow:dd_load_tuning_search_help    | dd_load_dds_dag | dd_load_tuning_search_help    | JOB           |                     | Loading information about systems and types into tuning.search_help table | urn:job:dd:airflow:dd_load_tuning_search_help dd_load_tuning_search_help       |         |        |             | {'type_for_search': 'Job', 'system_for_search': 'Data Detective'} |                |         |         |                 |          |        |
| urn:job:dd:airflow:dd_system_remove_works        | dd_load_dds_dag | dd_system_remove_works        | JOB           |                     | Clean of unremoved works                                                  | urn:job:dd:airflow:dd_system_remove_works dd_system_remove_works               |         |        |             | {'type_for_search': 'Job', 'system_for_search': 'Data Detective'} |                |         |         |                 |          |        |