- ### MovieLens
> **Descriptions:** MovieLens is a widely used benchmark dataset in movie recommendations. Among them, MovieLens-1M consists of approximately 1 million explicit ratings (ranging from 1 to 5) on the MovieLens website while MovieLens-2M consists of approximately 20 million explicit ratings (ranging from 1 to 5) on the Movie- Lens website.

|                    | Statistics(V1) | Statistics(V2) |
| ------------------ | -------------- | -------------- |
| **Users**          | 6036           | 138159         |
| **Items**          | 2347           | 16954          |
| **Interactions**   | 753772         | 13501622       |
| **Entities**       | /              | 102569         |
| **Relation Types** | /              | 32             |
| **Triples**        | 20195          | 499474         |

> **Link:** 
>
> V1: <https://github.com/hwwang55/RippleNet/tree/master/data/movie>
>
> V2:  <https://github.com/hwwang55/KGCN/tree/master/data/movie>

| Papers utilizing the dataset             |
| ---------------------------------------- |
| RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems **(V1)** |
| Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation **(V1)** |
| Knowledge Graph Convolutional Networks for Recommender Systems **(V2)** |


<br/>



- ### MovieLen + IMDb

> **Descriptions:** The combination of MovieLens and IMDb datasets, named MI, which are linked by the titles and release dates of movies. In particular, MovieLens offers the user-item interaction data, while IMDb offers the item-item interaction data, which serves as the KG part that contains auxiliary information on movies, such as genre, actor, director, and writer. The two datasets are linked by the titles and release dates
> of movies.

|                    | Statistics(V1) | Statistics(V2) |
| ------------------ | -------------- | -------------- |
| **Users**          | 6040           | 943            |
| **Items**          | 3859           | 1682           |
| **Interactions**   | 998034         | 10000          |
| **Entities**       | 11462          | /              |
| **Entity Types**   | 4              | /              |
| **Relation Types** | 6              | 5              |
| **Triples**        | 1017030        | 924759         |

> **Link:**
>
> V1: NOT FOUND YET
>
> V2: <https://github.com/XinGla/RCF/tree/master/ML100K>

| Papers utilizing the dataset             |
| ---------------------------------------- |
| Explainable Reasoning over Knowledge Graphs for Recommendation **(V1)** |
| Relational Collaborative Filtering: Modeling Multiple Item Relations for Recommendation **(V2)** |





- ### Book-Crossing 

> **Descriptions:** Book-Crossing contains 1 million ratings (ranging from 0 to 10) of books in the Book-Crossing community.

|                    | Statistics(V1) | Statistics(V2) | Statistics(V3) |
| ------------------ | -------------- | -------------- | -------------- |
| **Users**          | 17860          | 17860          | 19676          |
| **Items**          | 14967          | 14910          | 20003          |
| **Interactions**   | 139746         | 139746         | 172576         |
| **Entities**       | /              | /              | 25787          |
| **Relation Types** | /              | /              | 18             |
| **Triples**        | /              | /              | 60787          |

> **Link:** 
>
> V1: <https://github.com/hwwang55/RippleNet/tree/master/data/book>
>
> V2: <https://github.com/hwwang55/MKR/tree/master/data/book>
>
> V3: NOT FOUND

| Papers utilizing the dataset             |
| ---------------------------------------- |
| RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems **(V1)** |
| Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation **(V2)** |
| Knowledge Graph Convolutional Networks for Recommender Systems **(V3)** |





- ### Bing-News

> **Descriptions:** Bing-News dataset contains  the server logs of Bing News from October 16, 2016 to August 11, 2017. Each piece of news has a title and a snippet.

|                    | Statistics   |
| ------------------ | ------------ |
| **Users**          | 141487       |
| **Items**          | 535145       |
| **Interactions**   | 1025192      |
| **Entities**       | 336350       |
| **Relation Types** | no statistic |
| **Triples**        | 1545217      |

> **Link:** <https://github.com/hwwang55/DKN/tree/master/data>

| Papers utilizing the dataset             |
| ---------------------------------------- |
| RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems |
| Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation |
| DKN: Deep Knowledge-Aware Network for News Recommendation |





- ### Last.FM

> **Descriptions:** This is the music listening dataset collected from Last.fm online music systems. Wherein, the tracks are viewed as the items.

|                    | Statistics(V1) | Statistics(V2) |
| ------------------ | -------------- | -------------- |
| **Users**          | 23566          | 1872           |
| **Items**          | 48123          | 3846           |
| **Interactions**   | 3034796        | 42346          |
| **Entities**       | 90961          | 9366           |
| **Entity Types**   | /              | /              |
| **Relation Types** | 9              | 60             |
| **Triples**        | 464567         | 15518          |

> V1 is the subset of the dataset where the timestamp is from Jan, 2015 to June, 2015. while V2 is a
> set of 2 thousand users from Last.fm online music system.

> **Link:**
>
> V1:  https://github.com/xiangwang1223/knowledge_graph_attention_network/tree/master/Data/yelp2018>
>
> V2: <https://github.com/hwwang55/KGCN/tree/master/data/music>

| Papers utilizing the dataset             |
| ---------------------------------------- |
| KGAT: Knowledge Graph Attention Network for Recommendation **(V1)** |
| Knowledge Graph Convolutional Networks for Recommender Systems **(V2)** |
| Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation **(V2)** |





- ### Amazon e-commerce datasets collection 

> **Descriptions:**  The dataset is consisting of product reviews and meta information from Amazon.com. The datasets include four categories: CDs and Vinyl, Clothing, Cell Phones and Beauty. Each category is considered as an individual benchmark that constitutes a knowledge graph containing 5 types of entities and 7 types of relations.

|                    | CDs & Vinyl | Clothing | Cell Phones | Beauty |
| ------------------ | ----------- | -------- | ----------- | ------ |
| **Users**          | 75258       | 39387    | 27879       | 22363  |
| **Items**          | 64443       | 23033    | 10429       | 12101  |
| **Entities Types** | 5           | 5        | 5           | 5      |
| **Relation Types** | 8           | 8        | 8           | 8      |

> **Note:**
>
> | **Entities** | **Descriptions**                     |
> | ------------ | ------------------------------------ |
> | User         | User in recommender system           |
> | Item         | Product to be recommended to users   |
> | Feature      | A product feature word from reviews  |
> | Brand        | Brand or manufacturer of the product |
> | Category     | Category of the product              |
>
> | **Relations**   | **Descriptions**                  |
> | --------------- | --------------------------------- |
> | Purchase        | User purchase Tem                 |
> | Mention         | User mention Feature              |
> | Described_by    | Item described_by Feature         |
> | Belong_to       | Item belong_to Category           |
> | Produced_by     | Item produced_by Brand            |
> | Also_bought     | Item also_bought Item             |
> | Also_viewed     | Item also_view another Item       |
> | Bought_together | Item bought_together another Item |

> **Link:** <https://github.com/orcax/PGPR/tree/master/data> (Note: only Cell Phones and Beauty available)

| Papers utilizing the dataset             |
| ---------------------------------------- |
| Reinforcement Knowledge Graph Reasoning for Explainable Recommendation |





- ### KKBox

> **Descriptions:** This dataset is adopted from the WSDM Cup 2018 Challenge7 and is provided by the music streaming service KKBox. Besides the user-item interaction data, this dataset also contains
> description of music, which can help us to introduce the item relations.

|                    | Statistics(V1) | Statistics(V2) |
| ------------------ | -------------- | -------------- |
| **Users**          | 34403          | 24613          |
| **Items**          | 2296833        | 61877          |
| **Interactions**   | 3714655        | 2170690        |
| **Entities**       | 2851220        | /              |
| **Entity Types**   | 4              | /              |
| **Relation Types** | 6              | 6              |
| **Triples**        | 11182682       | /              |

> **Note:** V1 is the whole dataset while V2 is processed by removing the songs that have missing description.

> **Link:**
>
> V1: <https://github.com/eBay/KPRN/tree/master/release/songPathRnn/data/input>
>
> V2: <https://github.com/XinGla/RCF/tree/master/KKBOX_data>

| Papers utilizing the dataset             |
| ---------------------------------------- |
| Explainable Reasoning over Knowledge Graphs for Recommendation **(V1)** |
| Relational Collaborative Filtering: Modeling Multiple Item Relations for Recommendation **(V2)** |





- ### MSN News (For news recommendation particularly)

> **Descriptions:** This dataset was constructed by randomly sampling user logs from MSN News
> in one month

|                                          | Statistics(V1) | Statistics(V2) |
| ---------------------------------------- | -------------- | -------------- |
| **Users**                                | 25000          | 10000          |
| **News**                                 | 38501          | 42255          |
| **Impressions** ( a behavior like clicking a news ) | 393191         | 445230         |

> **Note:** The logs of V1 is collected  from December 23rd, 2018 to January 19th, 2019 while the logs of V2 is collected from December 13rd, 2018 to January 12nd, 2019.

> **Link:** https://www.msn.com/en-us/news (Note: the dataset is not processed)

| Papers utilizing the dataset             |
| ---------------------------------------- |
| Neural News Recommendation with Long- and Short-term User Representations **(V1)** |
| Neural News Recommendation with Attentive Multi-View Learning **(V2)** |
| NPA: Neural News Recommendation with Personalized Attention **(V2)** |





- ### Amazon-book

> **Description:** Amazon-review is a widely used dataset for product recommendation [10]. We select Amazon-book from this collection.

|                     | Statistics |
| ------------------- | ---------- |
| **Users**           | 70679      |
| **Items**           | 24915      |
| **Interactions**    | 847733     |
| **Entities**        | 88572      |
| **Relations Types** | 39         |
| **Triples**         | 2557746    |

> **Link:**<https://github.com/xiangwang1223/knowledge_graph_attention_network/tree/master/Data/amazon-book>

| Papers utilizing the dataset             |
| ---------------------------------------- |
| KGAT: Knowledge Graph Attention Network for Recommendation |





- ### Yelp2018

> **Description:** This dataset is adopted from the 2018 edition of the Yelp challenge. Here we view the local businesses like restaurants and bars as the items. Similarly, we use the 10-core setting to ensure that each user and item have at least ten interactions.

|                     | Statistics |
| ------------------- | ---------- |
| **Users**           | 45919      |
| **Items**           | 45538      |
| **Interactions**    | 1185068    |
| **Entities**        | 90961      |
| **Relations Types** | 42         |
| **Triples**         | 1853704    |

> **Link:**<https://github.com/xiangwang1223/knowledge_graph_attention_network/tree/master/Data/yelp2018>

| Papers utilizing the dataset             |
| ---------------------------------------- |
| KGAT: Knowledge Graph Attention Network for Recommendation |

