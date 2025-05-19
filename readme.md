#### Dataset
For each dataset file, we provided the question-answering data (train and test, e.g. Prime_train_QA_with_topic_entity.json and Prime_test_QA_with_topic_entity.json
The data structure of ADint_KG.txt,

```
e.g.
137690    1    34589
1         3    144772
...
```
each  line refers to a triple (head entity id (e.g.137690), relation id(e.g.1), tail entity id(e.g.34589))


**edge_type_dict.pkl**
{0: 'ppi', 1: 'carrier', 2: 'enzyme', 3: 'target', 4: 'transporter', 5: 'contraindication', 6: 'indication', 7: 'off-label use', 8: 'synergistic interaction', 9: 'associated with', 10: 'parent-child', 11: 'phenotype absent', 12: 'phenotype present', 13: 'side effect', 14: 'interacts with', 15: 'linked to', 16: 'expression present', 17: 'expression absent'}

**node_info.pkl**
{0: {'details': {'\_id': '9796',
'\_score': 17.934021,
'alias': ['DYRK1AP3', 'PAHX-AP', 'PAHXAP1'],
'genomic_pos': {'chr': '8',
'end': 22232101,
'ensemblgene': 'ENSG00000168490',
'start': 22219703,
'strand': -1},
'name': 'phytanoyl-CoA 2-hydroxylase interacting protein',
'query': 'PHYHIP',
'summary': 'Enables protein tyrosine kinase binding activity. '
'Involved in protein localization. Located in '
'cytoplasm. [provided by Alliance of Genome '
'Resources, Apr 2022]'},
'id': 9796,
'name': 'PHYHIP',
'source': 'NCBI',
'type': 'gene/protein'}}

**node_type_dict.pkl**
{0: 'disease', 1: 'gene/protein', 2: 'molecular_function', 3: 'drug', 4: 'pathway', 5: 'anatomy', 6: 'effect/phenotype', 7: 'biological_process', 8: 'cellular_component', 9: 'exposure'}

