# Reproducibility Checklist

> Copy this file and fill in the **Value** column. For fields marked *(see Scoring Guide)*, pick one option from the [Scoring Guide](#scoring-guide) below.

| Field | Value |
|:---|:---|
| **Title** | |
| **Link** | |
| **Github** | |
| **Type I** | |
| **Type II** | |
| **Code acquisition**<br>(Can be downloaded) | none |
| **Execution Protocol**<br>(Readme can be followed) | none |
| **Models-based**<br>(Open-source LLM, and GPT family) | |
| **Other models** | |
| **Execution Time (total)** | |
| **Setup time**<br>(no more than 2 hrs) | |
| **Debugging time**<br>(no more than 2 hrs) | |
| **Failure Classification**<br>(see Scoring Guide) | none |
| **Failure explanation**<br>(required if Failure Classification is "others") | |
| **Attack or defense success rate** | |
| **Official attack or defense success rate** | |
| **Performance**<br>(e.g. attack efficiency, query counts) | |
| **README Quality**<br>(see Scoring Guide) | none |
| **Out-of-box usability**<br>(see Scoring Guide) | none |
| **Result matching**<br>(see Scoring Guide) | none |
| **Experimental setup determinism**<br>(see Scoring Guide) | none |
| **Other comments or opinions** | |

---

## Scoring Guide

### Failure Classification
- non-functional, spend more than 2 hrs to set up
- Time out, stuck more than 12 hrs
- non-functional, spend more than 2 hrs for debugging
- others (explain in **Failure explanation**)
- none

### README Quality
| Score | Description |
|:---|:---|
| 1-Terrible | Critical information missing, unusable documentation |
| 3-Poor | Severely lacking environment setup, poor target description, confusing steps |
| 6-Average | Basic environment details, basic target description, simple execution instructions |
| 8-Good | Adequate environment details, good target description, clear execution guidance |
| 10-Excellent | Well-documented environment, clear target info, thorough step-by-step instructions |
| none | Not evaluated |

### Out-of-box usability
| Score | Description |
|:---|:---|
| 1-Terrible | Non-functional installation, missing critical components, unusable out-of-box |
| 3-Poor | Missing dependencies, difficult installation, hard-to-find data, complicated config |
| 6-Average | Basic requirements file, standard installation process, data mostly available |
| 8-Good | Adequate dependency list, manageable installation, accessible datasets, some setup needed |
| 10-Excellent | Comprehensive dependencies, easy installation, accessible data, simple setup |
| none | Not evaluated |

### Result matching
| Score | Description |
|:---|:---|
| 1-Terrible | Complete failure to reproduce results, within 25% or lower of paper claims |
| 3-Poor | Major success rate discrepancies, low-quality samples, within 50% of paper claims |
| 6-Average | Acceptable success rate variance, basic sample quality, within 30% of paper claims |
| 8-Good | Reasonable success rate match, decent sample similarity, within 10% of paper claims |
| 10-Excellent | High success rate consistency, very similar samples, within 5% of paper claims |
| none | Not evaluated |

### Experimental setup determinism
| Score | Description |
|:---|:---|
| 1-Terrible | Complete lack of determinism, unreproducible setup, random experimental conditions |
| 3-Poor | Poor seed management, vague data divisions, variable model configurations |
| 6-Average | Some seed control, standard data splitting, acceptable model initialization |
| 8-Good | Good seed management, clear data divisions, consistent model configurations |
| 10-Excellent | Comprehensive seed control, well-defined splits, mostly deterministic setup |
| none | Not evaluated |
