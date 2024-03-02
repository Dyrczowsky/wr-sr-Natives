# Workers

Base Needs:

|            Method | return type |
| ----------------: | ----------: |
|  fStatusHappiness |       float |
|       fStatusFood |       float |
|     fStatusHealth |       float |
|     fStatusSoviet |       float |
|    fStatusAlcohol |       float |
|    fStatusCulture |       float |
|      fStatusSport |       float |
|   fStatusReligion |       float |
|   fStatusClothing |       float |
| fStatusElectronic |       float |
|      fStatusCrime |       float |

Extra Info:

|                Method | return type | Comment                                   |
| --------------------: | ----------: | :---------------------------------------- |
|             vPosition |     vector3 |
|          nTouristFlag |         int | 0 - not tourist, 1 - soviet, 2 - wester   |
|                  fAge |       float |
|            fEducation |       float |
|               bIsHome |        char |
|         bIsUnemployed |        char |
|  bIsUnemployedDueKids |        char |
|            nValidRead |         int |
|  bWorkplaceAsProfesor |        char |
| bWorkOnReconstruction |        char |
|    nForeignWorkerFlag |         int | 0 - not a foreign, 1 - soviet, 2 - wester |
| nDemandUnsatisfiedNum |         int |
|    nDemandUnsatisfied |      int[7] |
|             nParentID |         int |

Example:

```py

worker = Person_GetByTag("TAG")
worker.fStatusHappiness

```
