# Search Programming problem
Provides instructions about problem 

# Sample product data

{"product_id":"<fill>","sellerId":"<fill>","title":"<fill>","manufacturer":"<fill>","price":{"range":"<fill>","min":<fill>,"max":<fill>},"isLowQuantity":false,"isSoldOut":false,"isBackorder":false,"metafields":[{"key":"Capacity","value":"<fill>"},{"key":"<fill>","value":"<fill>"}],"requiresShipping":true,"isVisible":true,"publishedAt":{"$date":"2020-02-12T08:05:39.743Z"},"createdAt":{"$date":"2010-08-23T05:53:16.134Z"},"updatedAt":{"$date":"2019-08-23T05:53:16.134Z"},"workflow":{"status":"new"}}

{"product_id":"121234353567786","sellerId":"87866","title":"Voltas 1.5 Ton Adjustable Inverter 5 Star Copper (2019 Range) 185V ADS (R32) Split AC (White)","pageTitle":"Voltas 1.5 Ton Adjustable Inverter.","description":"Stay at ease even when the mercury hits the roof by opting for this Voltas Inverter Adjustable Split AC. It has a capacity of 1.5 tons, hence it can cover a large area, while the 5-star energy rating helps you to reduce electricity costs significantly. It ensures stabilizer free operation so that it stays protected against voltage fluctuations. The 100 percent copper make ensures optimum performance as well as energy efficiency. (Star rating of model is as per 2018/2019 BEE rating, manufacturing can be of 2019 or before)","manufacturer":"Voltas","price":{"range":"24999","min":24999,"max":24999},"isLowQuantity":false,"isSoldOut":false,"isBackorder":false,"metafields":[{"key":"Capacity","value":"1.5 ton"},{"key":"Rating","value":"Inverter 5 Star"}],"requiresShipping":true,"isVisible":true,"publishedAt":{"$date":"2020-02-12T08:05:39.743Z"},"createdAt":{"$date":"2010-08-23T05:53:16.134Z"},"updatedAt":{"$date":"2019-08-23T05:53:16.134Z"},"workflow":{"status":"new"}}

# Programming Problem

* Write kafka producer which can generate above at least 100000 recrods based on above template of data. Placeholders in the template can be replaced from given set of 100 different values. developers can define their own values 

* Above producer should write data into a kafka topic called "product_details_search"

* Use kafka topic "product_details_search" as data source for search. Developers can chose Apache Solr or Elastic search or any other open source search engine to index above data 

* Showcase quality of search results 

* Write automated tests to test the results
