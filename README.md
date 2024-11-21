# Central Data Repository
This repository contains a collection of tweet IDs collected using the Twitter Academic API during the REMISS project, 
focusing on election campaigns in Spain and discussions about migration. We used the Twitter’s search to 
gather historical tweets and the streaming API to follow specified accounts and also collect in real-time tweets that 
mention specific keywords. To comply with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), 
we are only publicly releasing the tweet IDs of the collected tweets. The data is released for non-commercial research use. 

**With Twitter's recent changes to its Academic API policies, it’s no longer possible to collect or rehydrate tweets 
as we did during the project development**

# Datasets
## Political elections
- Barcelona town elections 2019
- Andalusia regional elections 2022

### Statistics summary
|                   | Barcelona 2019    | Andalucia 2022    |
| --                | ----              | ----              |
| Number of tweets  | 3,328,189         | 3,193,589         |
| Number of authors | 275,039           | 170,872           |
| First tweet date  | 2019-04-01        | 2022-04-01        |
| Last tweet date   | 2019-06-30        | 2022-08-29        |

## Migration
- Open Arms: alleged connection between Open Arms and criminal organizations [[1]]
- Ayudas: alleged financial support for unaccompanied foreign minors (MENAs) [[1]][[2]]
- Agresiones: alleged link between assaults and unaccompanied foreign minors (MENAs) [[3]][[4]]
- Cambrils: assault by a supposed unaccompanied foreign minor (MENA) [[5]]

### Statistics summary
|                   | Open Arms     | Ayudas        | Agresiones    | Cambrils      |
| --                | ----          | ----          | ----          | ----          |
| Number of tweets  | 88,097        | 198,135       | 186,768       | 880           |
| Number of authors | 36,270        | 64,771        | 79,073        | 827           |
| First tweet date  | 2015-10-12    | 2019-06-14    | 2020-01-01    | 2021-07-06    |![](../../../Desktop/metriques-1.png)
| Last tweet date   | 2023-03-18    | 2023-03-31    | 2023-03-31    | 2021-07-16    |

[1]: https://www.newtral.es/verificamos-varios-de-los-tuits-de-vox-sobre-el-open-arms-durante-el-discurso-de-calvo/20190829/
[2]: https://www.verificat.cat/fact-check/els-menors-no-acompanyats-no-cobren-1.125-euros-al-mes-a-la-comunitat-valenciana-com-afirma-un-tuit-viral
[3]: https://www.verificat.cat/fact-check/les-comunitats-autonomes-amb-mes-violacions-grupals-no-son-les-que-tenen-mes-presencia-de-menors-estrangers-no-acompanyats
[4]: https://www.verificat.cat/fact-check/andalusia-no-acumula-el-75-de-les-violacions-despanya-ni-la-majoria-son-comeses-per-estrangers
[5]: https://www.verificat.cat/fact-check/el-jove-que-va-agredir-el-conserge-dun-hotel-de-cambrils-no-es-un-menor-estranger-no-acompanyat