# UseGalaxy.eu Workflow Testing

Based off of [jmchilton's template](https://github.com/jmchilton/planemo-workflow-test-template), except running tests against UseGalaxy.eu

## Testing

We are [automatically running](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/) these workflows against UseGalaxy.eu

Workflow                                                                                     | Status
---                                                                                          | ---
example1/wf3-shed-tools.ga                                                                   | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example1%2Fwf3-shed-tools.ga/badge/icon                                                                       )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example1%2Fwf3-shed-tools.ga/)
example2/wf4-shed-tools.ga                                                                   | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example2%2Fwf4-shed-tools.ga/badge/icon                                                                       )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example2%2Fwf4-shed-tools.ga/)
HiCExplorer/scratch-to-contact.ga                                                            | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=HiCExplorer%2Fscratch-to-contact.ga/badge/icon                                                                )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=HiCExplorer%2Fscratch-to-contact.ga/)
example_blockclust/blockclust_workflow.ga                                                    | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example_blockclust%2Fblockclust_workflow.ga/badge/icon                                                        )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example_blockclust%2Fblockclust_workflow.ga/)
training/variant-analysis/microbial-variants/microbial_variant_calling.ga                    | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fvariant-analysis%2Fmicrobial-variants%2Fmicrobial_variant_calling.ga/badge/icon                    )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fvariant-analysis%2Fmicrobial-variants%2Fmicrobial_variant_calling.ga/)
training/sequence-analysis/quality-control/quality_control.ga                                | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fquality-control%2Fquality_control.ga/badge/icon                                )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fquality-control%2Fquality_control.ga/)
training/sequence-analysis/mapping/mapping.ga                                                | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fmapping%2Fmapping.ga/badge/icon                                                )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fmapping%2Fmapping.ga/)
training/chip-seq/formation_of_super-structures_on_xi/formation_of_super_structures_on_xi.ga | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fchip-seq%2Fformation_of_super-structures_on_xi%2Fformation_of_super_structures_on_xi.ga/badge/icon )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fchip-seq%2Fformation_of_super-structures_on_xi%2Fformation_of_super_structures_on_xi.ga/)
training/epigenetics/methylation-seq/methylation-seq.ga                                      | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fepigenetics%2Fmethylation-seq%2Fmethylation-seq.ga/badge/icon                                      )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fepigenetics%2Fmethylation-seq%2Fmethylation-seq.ga/)
training/assembly/general-introduction/assembly-general-introduction.ga                      | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Fgeneral-introduction%2Fassembly-general-introduction.ga/badge/icon                      )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Fgeneral-introduction%2Fassembly-general-introduction.ga/)
training/assembly/unicycler-assembly/unicycler.ga                                            | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Funicycler-assembly%2Funicycler.ga/badge/icon                                            )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Funicycler-assembly%2Funicycler.ga/)
training/metagenomics/general-tutorial/amplicon.ga                                           | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fmetagenomics%2Fgeneral-tutorial%2Famplicon.ga/badge/icon                                           )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fmetagenomics%2Fgeneral-tutorial%2Famplicon.ga/)
training/transcriptomics/ref-based/ref_based.ga                                              | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Ftranscriptomics%2Fref-based%2Fref_based.ga/badge/icon                                              )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Ftranscriptomics%2Fref-based%2Fref_based.ga/)
GraphClust2/GC-lite.ga                                                                       | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=GraphClust2%2FGC-lite.ga/badge/icon                                                                           )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=GraphClust2%2FGC-lite.ga/)
sklearn/ard/ard.ga                                                                       | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=sklearn%2Fard%2Fard.ga/badge/icon)](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=sklearn%2Fard%2Fard.ga/)
sklearn/adaboost/adaboost.ga                                                                       | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=sklearn%2Fadaboost%2Fadaboost.ga/badge/icon)](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=sklearn%2Fadaboost%2Fadaboost.ga/)
training/variant-analysis/mapping-by-sequencing/mapping_by_sequencing.ga                          | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fvariant-analysis%2Fmapping-by-sequencing%2Fmapping_by_sequencing.ga/badge/icon)](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fvariant-analysis%2Fmapping-by-sequencing%2Fmapping_by_sequencing.ga/)
training/proteomics/protein-id-sg-ps/protein-id-sg-ps.ga                                         | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fproteomics%2Fprotein-id-sg-ps%2Fprotein-id-sg-ps-test.yml/55/badge/icon)](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fproteomics%2Fprotein-id-sg-ps%2Fprotein-id-sg-ps.ga/)
training/proteomics/protein_quant_sil/protein_quant_sil.ga                                      | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fproteomics%2Fprotein_quant_sil%2Fprotein_quant_sil-test.yml/55/badge/icon)](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fproteomics%2Fprotein_quant_sil%2Fprotein_quant_sil.ga/)

## Pretty-printing Worfklow JSON

You can use the command line tool `jq` to pretty-print the workflow .ga files:

```console
cat wf.ga | jq . -S > out.ga
```

or this webservice: https://jsonformatter.org/
