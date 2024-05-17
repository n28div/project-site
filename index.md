---
layout: default
---

```SPARQL
PREFIX arco-catalogue: <https://w3id.org/arco/ontology/catalogue/>
SELECT *
WHERE{
  ?record arco-catalogue:hasCatalogueRecordVersion ?recordVersion . 
  ?recordVersion arco-catalogue:editedAtTime ?time .
  ?time rdfs:label ?timeLabel
}
limit 100
```

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/Palazzo_Poggi_UniBo.jpg/220px-Palazzo_Poggi_UniBo.jpg)
