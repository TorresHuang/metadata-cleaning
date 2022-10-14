# SPECIES

## 使用名称用法（Working with Name Usages）

## 相关接口
	* /species/{int}
		+ Method：GET
		+ 描述：获取单个名称的用法
		+ 是否换页：否
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/5231190>

```
{
	  "key": 5231190,
	  "nubKey": 5231190,
	  "nameKey": 8290258,
	  "taxonID": "gbif:5231190",
	  "sourceTaxonKey": 172761619,
	  "kingdom": "Animalia",
	  "phylum": "Chordata",
	  "order": "Passeriformes",
	  "family": "Passeridae",
	  "genus": "Passer",
	  "species": "Passer domesticus",
	  "kingdomKey": 1,
	  "phylumKey": 44,
	  "classKey": 212,
	  "orderKey": 729,
	  "familyKey": 5264,
	  "genusKey": 2492321,
	  "speciesKey": 5231190,
	  "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	  "constituentKey": "7ddf754f-d193-4cc9-b351-99906754a03b",
	  "parentKey": 2492321,
	  "parent": "Passer",
	  "basionymKey": 8933000,
	  "basionym": "Fringilla domestica Linnaeus, 1758",
	  "scientificName": "Passer domesticus (Linnaeus, 1758)",
	  "canonicalName": "Passer domesticus",
	  "vernacularName": "家麻雀",
	  "authorship": "(Linnaeus, 1758) ",
	  "nameType": "SCIENTIFIC",
	  "rank": "SPECIES",
	  "origin": "SOURCE",
	  "taxonomicStatus": "ACCEPTED",
	  "nomenclaturalStatus": [],
	  "remarks": "",
	  "publishedIn": "Syst. Nat. ed. 10 p. 183",
	  "numDescendants": 15,
	  "lastCrawled": "2021-11-29T13:11:38.124+00:00",
	  "lastInterpreted": "2021-11-29T12:30:57.140+00:00",
	  "issues": [],
	  "synonym": false,
	  "class": "Aves"
}
```

## 相关接口
	* /species/{int}/verbatim
		+ Method：GET
		+ 描述：获取单个名称的用法
		+ 是否换页：否
		+ 参数：无
		+ 接口示例：<https://api.gbif.org/v1/species/101683527/verbatim>

```
{
	  "key": 101683527,
	  "extensions": {
	    "http://rs.gbif.org/terms/1.0/VernacularName": [
	      {
	        "http://rs.tdwg.org/dwc/terms/vernacularName": "spiny-headed worms",
	        "http://purl.org/dc/terms/language": "English"
	      },
	      {
	        "http://rs.tdwg.org/dwc/terms/vernacularName": "thorny-headed worms",
	        "http://purl.org/dc/terms/language": "English"
	      },
	      {
	        "http://rs.tdwg.org/dwc/terms/vernacularName": "acantocéfalo",
	        "http://purl.org/dc/terms/language": "Portuguese"
	      }
	    ],
	    "http://rs.gbif.org/terms/1.0/Reference": [
	      {
	        "http://purl.org/dc/terms/publisher": "Sinauer Associates, Inc.",
	        "http://purl.org/dc/terms/date": "1990-01-01",
	        "http://purl.org/dc/terms/creator": "Brusca, Richard C., and Gary J. Brusca",
	        "http://purl.org/dc/terms/source": "Invertebrates",
	        "http://purl.org/dc/terms/bibliographicCitation": "Brusca, Richard C., and Gary J. Brusca, 1990: null. Invertebrates. xiii + 992.",
	        "http://unknown.org/http////itis.org/terms/ISBN": "0-87893-098-1",
	        "http://unknown.org/http////itis.org/terms/pages": "xiii + 992"
	      },
	      {
	        "http://purl.org/dc/terms/date": "2003-01-01",
	        "http://purl.org/dc/terms/creator": "Bhattacharya, S. B., and S. Banerjee",
	        "http://purl.org/dc/terms/title": "New record of the genus Gorgorhynchoides Cable & Linderoth, 1963 (Acanthocephala: Palaeacanthocephala) with G. indicus n. sp. from carangeid fish of Indian coast",
	        "http://purl.org/dc/terms/source": "Records of the Zoological Survey of India, vol. 101, part 3-4",
	        "http://purl.org/dc/terms/bibliographicCitation": "Bhattacharya, S. B., and S. Banerjee, 2003: New record of the genus Gorgorhynchoides Cable & Linderoth, 1963 (Acanthocephala: Palaeacanthocephala) with G. indicus n. sp. from carangeid fish of Indian coast. Records of the Zoological Survey of India, vol. 101, part 3-4. 49-54.",
	        "http://unknown.org/http////itis.org/terms/ISSN": "0375-1511",
	        "http://unknown.org/http////itis.org/terms/pages": "49-54"
	      },
	      {
	        "http://purl.org/dc/terms/date": "2013-09-19",
	        "http://purl.org/dc/terms/creator": "Amin, Omar M.",
	        "http://purl.org/dc/terms/title": "Classification of the Acanthocephala",
	        "http://purl.org/dc/terms/source": "Folia Parasitologica, vol. 60, no. 4",
	        "http://purl.org/dc/terms/bibliographicCitation": "Amin, Omar M., 2013: Classification of the Acanthocephala. Folia Parasitologica, vol. 60, no. 4. 273-305.",
	        "http://unknown.org/http////itis.org/terms/ISSN": "0015-5683",
	        "http://unknown.org/http////itis.org/terms/pages": "273-305"
	      }
	    ]
	  },
	  "lastCrawled": "2022-09-15T04:04:02.852+00:00",
	  "http://rs.tdwg.org/dwc/terms/scientificNameAuthorship": "Rudolphi, 1802",
	  "http://unknown.org/http////itis.org/terms/completeness": "complete",
	  "http://rs.tdwg.org/dwc/terms/taxonID": "64238",
	  "http://rs.tdwg.org/dwc/terms/taxonomicStatus": "valid",
	  "http://rs.tdwg.org/dwc/terms/taxonRank": "Phylum",
	  "http://rs.tdwg.org/dwc/terms/scientificName": "Acanthocephala",
	  "http://rs.tdwg.org/dwc/terms/parentNameUsageID": "914160"
}
```

## 相关接口
	* /species/{int}/name
		+ Method：GET
		+ 描述：获取一个解析名称的名称用法
		+ 是否换页：否
		+ 参数：无
		+ 接口示例：<https://api.gbif.org/v1/species/5231190/name>

```
{
  "key": 8290258,
  "scientificName": "Passer domesticus (Linnaeus, 1758)",
  "type": "SCIENTIFIC",
  "genusOrAbove": "Passer",
  "specificEpithet": "domesticus",
  "bracketAuthorship": "Linnaeus",
  "bracketYear": "1758",
  "parsed": true,
  "parsedPartially": false,
  "canonicalName": "Passer domesticus",
  "canonicalNameWithMarker": "Passer domesticus",
  "canonicalNameComplete": "Passer domesticus (Linnaeus, 1758)",
  "rankMarker": "sp."
}
```

## 相关接口
	* /species/{int}/parents
		+ Method：GET
		+ 描述：列出名称用法的所有父用法
		+ 是否换页：否
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/5231190/parents>

```
[
	  {
	    "key": 1,
	    "nubKey": 1,
	    "nameKey": 63244318,
	    "taxonID": "gbif:1",
	    "sourceTaxonKey": 1,
	    "kingdom": "Animalia",
	    "kingdomKey": 1,
	    "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	    "constituentKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	    "scientificName": "Animalia",
	    "canonicalName": "Animalia",
	    "authorship": "",
	    "nameType": "SCIENTIFIC",
	    "rank": "KINGDOM",
	    "origin": "SOURCE",
	    "taxonomicStatus": "ACCEPTED",
	    "nomenclaturalStatus": [],
	    "remarks": "",
	    "numDescendants": 2843451,
	    "lastCrawled": "2021-11-29T13:11:38.124+00:00",
	    "lastInterpreted": "2021-11-29T11:38:58.565+00:00",
	    "issues": [],
	    "synonym": false
	  },
	  {
	    "key": 44,
	    "nubKey": 44,
	    "nameKey": 2429952,
	    "taxonID": "gbif:44",
	    "sourceTaxonKey": 172636724,
	    "kingdom": "Animalia",
	    "phylum": "Chordata",
	    "kingdomKey": 1,
	    "phylumKey": 44,
	    "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	    "constituentKey": "daacce49-b206-469b-8dc2-2257719f3afa",
	    "parentKey": 1,
	    "parent": "Animalia",
	    "scientificName": "Chordata",
	    "canonicalName": "Chordata",
	    "authorship": "",
	    "nameType": "SCIENTIFIC",
	    "rank": "PHYLUM",
	    "origin": "SOURCE",
	    "taxonomicStatus": "ACCEPTED",
	    "nomenclaturalStatus": [],
	    "remarks": "",
	    "numDescendants": 248378,
	    "lastCrawled": "2021-11-29T13:11:38.124+00:00",
	    "lastInterpreted": "2021-11-29T12:30:09.826+00:00",
	    "issues": [],
	    "synonym": false
	  },
	  {
	    "key": 212,
	    "nubKey": 212,
	    "nameKey": 1235940,
	    "taxonID": "gbif:212",
	    "sourceTaxonKey": 171152611,
	    "kingdom": "Animalia",
	    "phylum": "Chordata",
	    "kingdomKey": 1,
	    "phylumKey": 44,
	    "classKey": 212,
	    "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	    "constituentKey": "daacce49-b206-469b-8dc2-2257719f3afa",
	    "parentKey": 44,
	    "parent": "Chordata",
	    "scientificName": "Aves",
	    "canonicalName": "Aves",
	    "authorship": "",
	    "nameType": "SCIENTIFIC",
	    "rank": "CLASS",
	    "origin": "SOURCE",
	    "taxonomicStatus": "ACCEPTED",
	    "nomenclaturalStatus": [],
	    "remarks": "",
	    "numDescendants": 53045,
	    "lastCrawled": "2021-11-29T13:11:38.124+00:00",
	    "lastInterpreted": "2021-11-29T12:30:27.274+00:00",
	    "issues": [],
	    "synonym": false,
	    "class": "Aves"
	  },
	  {
	    "key": 729,
	    "nubKey": 729,
	    "nameKey": 8291655,
	    "taxonID": "gbif:729",
	    "sourceTaxonKey": 172752281,
	    "kingdom": "Animalia",
	    "phylum": "Chordata",
	    "order": "Passeriformes",
	    "kingdomKey": 1,
	    "phylumKey": 44,
	    "classKey": 212,
	    "orderKey": 729,
	    "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	    "constituentKey": "7ddf754f-d193-4cc9-b351-99906754a03b",
	    "parentKey": 212,
	    "parent": "Aves",
	    "scientificName": "Passeriformes",
	    "canonicalName": "Passeriformes",
	    "authorship": "",
	    "nameType": "SCIENTIFIC",
	    "rank": "ORDER",
	    "origin": "SOURCE",
	    "taxonomicStatus": "ACCEPTED",
	    "nomenclaturalStatus": [],
	    "remarks": "",
	    "numDescendants": 28979,
	    "lastCrawled": "2021-11-29T13:11:38.124+00:00",
	    "lastInterpreted": "2021-11-29T12:30:39.290+00:00",
	    "issues": [],
	    "synonym": false,
	    "class": "Aves"
	  },
	  {
	    "key": 5264,
	    "nubKey": 5264,
	    "nameKey": 8291641,
	    "taxonID": "gbif:5264",
	    "sourceTaxonKey": 175898058,
	    "kingdom": "Animalia",
	    "phylum": "Chordata",
	    "order": "Passeriformes",
	    "family": "Passeridae",
	    "kingdomKey": 1,
	    "phylumKey": 44,
	    "classKey": 212,
	    "orderKey": 729,
	    "familyKey": 5264,
	    "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	    "constituentKey": "7ddf754f-d193-4cc9-b351-99906754a03b",
	    "parentKey": 729,
	    "parent": "Passeriformes",
	    "scientificName": "Passeridae",
	    "canonicalName": "Passeridae",
	    "authorship": "",
	    "nameType": "SCIENTIFIC",
	    "rank": "FAMILY",
	    "origin": "SOURCE",
	    "taxonomicStatus": "ACCEPTED",
	    "nomenclaturalStatus": [],
	    "remarks": "",
	    "numDescendants": 242,
	    "lastCrawled": "2021-11-29T13:11:38.124+00:00",
	    "lastInterpreted": "2021-11-29T12:30:56.542+00:00",
	    "issues": [],
	    "synonym": false,
	    "class": "Aves"
	  },
	  {
	    "key": 2492321,
	    "nubKey": 2492321,
	    "nameKey": 8290085,
	    "taxonID": "gbif:2492321",
	    "sourceTaxonKey": 172761520,
	    "kingdom": "Animalia",
	    "phylum": "Chordata",
	    "order": "Passeriformes",
	    "family": "Passeridae",
	    "genus": "Passer",
	    "kingdomKey": 1,
	    "phylumKey": 44,
	    "classKey": 212,
	    "orderKey": 729,
	    "familyKey": 5264,
	    "genusKey": 2492321,
	    "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
	    "constituentKey": "7ddf754f-d193-4cc9-b351-99906754a03b",
	    "parentKey": 5264,
	    "parent": "Passeridae",
	    "scientificName": "Passer Brisson, 1760",
	    "canonicalName": "Passer",
	    "authorship": "Brisson, 1760",
	    "nameType": "SCIENTIFIC",
	    "rank": "GENUS",
	    "origin": "SOURCE",
	    "taxonomicStatus": "ACCEPTED",
	    "nomenclaturalStatus": [],
	    "remarks": "",
	    "publishedIn": "Ornithologie 1 p. 36 pl. 1 fig. 6",
	    "numDescendants": 106,
	    "lastCrawled": "2021-11-29T13:11:38.124+00:00",
	    "lastInterpreted": "2021-11-29T12:30:56.937+00:00",
	    "issues": [],
	    "synonym": false,
	    "class": "Aves"
  }
]
```

## 相关接口
	* /species/{int}/children
		+ Method：GET
		+ 描述：列出名称用法的所有直接子用法
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/5231190/children>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": true,
  "results": [
    {
      "key": 6090823,
      "nubKey": 6090823,
      "nameKey": 16675127,
      "taxonID": "gbif:6090823",
      "sourceTaxonKey": 172761641,
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Passeriformes",
      "family": "Passeridae",
      "genus": "Passer",
      "species": "Passer domesticus",
      "kingdomKey": 1,
      "phylumKey": 44,
      "classKey": 212,
      "orderKey": 729,
      "familyKey": 5264,
      "genusKey": 2492321,
      "speciesKey": 5231190,
      "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
      "constituentKey": "7ddf754f-d193-4cc9-b351-99906754a03b",
      "parentKey": 5231190,
      "parent": "Passer domesticus",
      "scientificName": "Passer domesticus bactrianus Zarudny & Kudashev, 1916",
      "canonicalName": "Passer domesticus bactrianus",
      "authorship": "Zarudny & Kudashev, 1916",
      "nameType": "SCIENTIFIC",
      "rank": "SUBSPECIES",
      "origin": "SOURCE",
      "taxonomicStatus": "ACCEPTED",
      "nomenclaturalStatus": [],
      "remarks": "",
      "numDescendants": 0,
      "lastCrawled": "2021-11-29T13:11:38.124+00:00",
      "lastInterpreted": "2021-11-29T12:30:57.177+00:00",
      "issues": [
        "NAME_PARENT_MISMATCH"
      ],
      "synonym": false,
      "class": "Aves"
    },
   ]
}
```

## 相关接口
	* /species/{int}/related
		+ Method：GET
		+ 描述：在其他检查表中列出所有相关的名称用法
		+ 是否换页：是
		+ 参数：language, datasetKey
		+ 接口示例：<https://api.gbif.org/v1/species/5231190/related>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": false,
  "results": [
    {
      "key": 163317344,
      "nubKey": 5231190,
      "nameKey": 8290258,
      "taxonID": "7016",
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Passeriformes",
      "family": "Passeridae",
      "species": "Passer domesticus",
      "kingdomKey": 163331996,
      "phylumKey": 163331997,
      "classKey": 163331998,
      "orderKey": 163331999,
      "familyKey": 163332001,
      "speciesKey": 163317344,
      "datasetKey": "0537763e-a1ad-492d-8d33-673fc65df39a",
      "parentKey": 163332001,
      "parent": "Passeridae",
      "scientificName": "Passer domesticus (Linnaeus, 1758)",
      "canonicalName": "Passer domesticus",
      "authorship": "(Linnaeus, 1758) ",
      "nameType": "SCIENTIFIC",
      "rank": "SPECIES",
      "origin": "SOURCE",
      "taxonomicStatus": "ACCEPTED",
      "nomenclaturalStatus": [],
      "numDescendants": 0,
      "lastCrawled": "2021-12-01T01:30:59.934+00:00",
      "lastInterpreted": "2020-03-30T05:52:18.027+00:00",
      "issues": [],
      "synonym": false,
      "class": "Aves"
    }
   ]
}
```


## 相关接口
	* /species/{int}/synonyms
		+ Method：GET
		+ 描述：列出名称用法的所有同义词
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/2973063/synonyms>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": true,
  "results": [
    {
      "key": 2973064,
      "nubKey": 2973064,
      "nameKey": 54547,
      "taxonID": "gbif:2973064",
      "sourceTaxonKey": 170882390,
      "kingdom": "Plantae",
      "phylum": "Tracheophyta",
      "order": "Fabales",
      "family": "Fabaceae",
      "genus": "Albizia",
      "species": "Albizia inundata",
      "kingdomKey": 6,
      "phylumKey": 7707728,
      "classKey": 220,
      "orderKey": 1370,
      "familyKey": 5386,
      "genusKey": 2972897,
      "speciesKey": 2973063,
      "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
      "constituentKey": "f7053f73-74fb-4c9f-ab63-de28c61140c2",
      "parentKey": 2972897,
      "parent": "Albizia",
      "acceptedKey": 2973063,
      "accepted": "Albizia inundata (Mart.) Barneby & J.W.Grimes",
      "scientificName": "Acacia inundata Mart.",
      "canonicalName": "Acacia inundata",
      "authorship": "Mart.",
      "nameType": "SCIENTIFIC",
      "rank": "SPECIES",
      "origin": "SOURCE",
      "taxonomicStatus": "HOMOTYPIC_SYNONYM",
      "nomenclaturalStatus": [],
      "remarks": "",
      "publishedIn": "Reise Bras. 1: 555 (1823)",
      "numDescendants": 0,
      "lastCrawled": "2021-11-29T13:11:38.124+00:00",
      "lastInterpreted": "2021-11-29T12:55:34.526+00:00",
      "issues": [],
      "synonym": true,
      "class": "Magnoliopsida"
    }
   ]
}
```

## 相关接口
	* /species/{int}/descriptions
		+ Method：GET
		+ 描述：列出名称用法的所有描述
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/5231190/descriptions>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": false,
  "results": [
    {
      "key": 31032583,
      "taxonKey": 5231190,
      "type": "Distribución",
      "language": "",
      "description": "Ecorregión (Hernández et al. (1992): South American Pacific mangroves (SAPm): Distrito Tumaco",
      "source": "Aves del departamento de Nariño, Colombia",
      "sourceTaxonKey": 114072928
    }
   ]
}
```

## 相关接口
	* /species/{int}/distributions
		+ Method：GET
		+ 描述：列出名称用法的所有分发内容
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/5231190/distributions>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": false,
  "results": [
    {
      "taxonKey": 5231190,
      "locationId": "CO:08549003; CO:13657000; CO:44378000",
      "source": "Lista de especies probables para tres fragmentos de Bosque seco en la región del Caribe Colombiano",
      "sourceTaxonKey": 120732475
    }
   ]
}
```

## 相关接口
	* /species/{int}/media
		+ Method：GET
		+ 描述：列出名称用法的所有媒体项目
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/148403721/media>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": true,
  "results": [
    {
      "type": "StillImage",
      "format": "image/png",
      "references": "http://doi.org/10.5281/zenodo.1437852",
      "title": "FIGURE 2. Colonies of some cyclostome bryozoans, in vivo, attached to polymetallic nodules. A–E, Pandanipora helix n. gen., n. sp.: A, specimen GLD4–09, Stn 190; B, specimen GLD4–12, Stn 262; C, specimen YMG4–07, Stn 143; D, specimen YMG4–13, Stn 295; E, specimen GLD 4–11, Stn 212. F, Tubuliporina sp. indet., specimen YMG18–01, Stn 7. G, H, Abyssoecia elevata n. gen., n. sp.: G, specimen GLD4–09, Stn 196; H, specimen GLD4–09, Stn 191. I, Discantenna metallica n. sp.: specimen GLD4–11, Stn 224. J, K, Frontohornera frontalis n. gen., n. sp.: J, specimen YMG4–07, Stn 124; K, specimen GLD4–11, Stn 210. L, Alyonushka hystricosa n. gen., n. sp.: specimen GLD4–09, Stn 199. M, Calyssopora volcano n. gen., n. sp.: specimen YMG18–01, Stn 33. N, O, Anyuta anastema n. gen., n. sp.: N, specimen GLD4–09, Stn 180; O, specimen YMG4–06, Stn 71. Scale bars: 1 mm.",
      "description": "FIGURE 2. Colonies of some cyclostome bryozoans, in vivo, attached to polymetallic nodules. A–E, Pandanipora helix n. gen., n. sp.: A, specimen GLD4–09, Stn 190; B, specimen GLD4–12, Stn 262; C, specimen YMG4–07, Stn 143; D, specimen YMG4–13, Stn 295; E, specimen GLD 4–11, Stn 212. F, Tubuliporina sp. indet., specimen YMG18–01, Stn 7. G, H, Abyssoecia elevata n. gen., n. sp.: G, specimen GLD4–09, Stn 196; H, specimen GLD4–09, Stn 191. I, Discantenna metallica n. sp.: specimen GLD4–11, Stn 224. J, K, Frontohornera frontalis n. gen., n. sp.: J, specimen YMG4–07, Stn 124; K, specimen GLD4–11, Stn 210. L, Alyonushka hystricosa n. gen., n. sp.: specimen GLD4–09, Stn 199. M, Calyssopora volcano n. gen., n. sp.: specimen YMG18–01, Stn 33. N, O, Anyuta anastema n. gen., n. sp.: N, specimen GLD4–09, Stn 180; O, specimen YMG4–06, Stn 71. Scale bars: 1 mm.",
      "source": "Grischenko, Andrei V.;Gordon, Dennis P.;Melnik, Viacheslav P.",
      "audience": "biologists",
      "created": "2018-09-25T00:00:00.000+00:00",
      "creator": "Grischenko, Andrei V.;Gordon, Dennis P.;Melnik, Viacheslav P.",
      "publisher": "Zenodo",
      "taxonKey": 148403721,
      "identifier": "https://zenodo.org/record/1437852/files/figure.png"
    }
   ]
}
```

## 相关接口
	* /species/{int}/references
		+ Method：GET
		+ 描述：列出名称用法的所有引用
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/5231190/references>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": true,
  "results": [
    {
      "taxonKey": 5231190,
      "citation": "Avibase - the world bird database.",
      "type": "basis of record",
      "source": "World Register of Marine Species",
      "sourceTaxonKey": 167504516
    }
   ]
}
```


## 搜索名称（Searching Names）

## 相关接口
	* /species
		+ Method：GET
		+ 描述：列出所有或某些共享完全相同规范名称（即无作者）的检查列表中的名称用法。
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species?name=Puma%20concolor>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": false,
  "results": [
    {
      "key": 2435099,
      "nubKey": 2435099,
      "nameKey": 9541887,
      "taxonID": "gbif:2435099",
      "sourceTaxonKey": 172721713,
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Carnivora",
      "family": "Felidae",
      "genus": "Puma",
      "species": "Puma concolor",
      "kingdomKey": 1,
      "phylumKey": 44,
      "classKey": 359,
      "orderKey": 732,
      "familyKey": 9703,
      "genusKey": 2435098,
      "speciesKey": 2435099,
      "datasetKey": "d7dddbf4-2cf0-4f39-9b2a-bb099caae36c",
      "constituentKey": "7ddf754f-d193-4cc9-b351-99906754a03b",
      "parentKey": 2435098,
      "parent": "Puma",
      "basionymKey": 2435104,
      "basionym": "Felis concolor Linnaeus, 1771",
      "scientificName": "Puma concolor (Linnaeus, 1771)",
      "canonicalName": "Puma concolor",
      "authorship": "(Linnaeus, 1771) ",
      "nameType": "SCIENTIFIC",
      "rank": "SPECIES",
      "origin": "SOURCE",
      "taxonomicStatus": "ACCEPTED",
      "nomenclaturalStatus": [],
      "remarks": "",
      "publishedIn": "Mantissa Plantarum vol.2 p.266",
      "numDescendants": 7,
      "lastCrawled": "2021-11-29T13:11:38.124+00:00",
      "lastInterpreted": "2021-11-29T12:32:32.943+00:00",
      "issues": [],
      "synonym": false,
      "class": "Mammalia"
    }
   ]
 }
```


## 相关接口
	* /species/match
		+ Method：GET
		+ 描述：果提供了分类并且strict未设置为true，那么如果仅为name参数找不到直接匹配，则默认匹配也会尝试与之匹配。
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/match?verbose=true&kingdom=Plantae&name=Oenante>

```
{
  "usageKey": 3034893,
  "scientificName": "Oenanthe L.",
  "canonicalName": "Oenanthe",
  "rank": "GENUS",
  "status": "ACCEPTED",
  "confidence": 85,
  "note": "Similarity: name=75; authorship=0; classification=4; rank=0; status=1; nextMatch=5",
  "matchType": "FUZZY",
  "alternatives": [
    {
      "usageKey": 2492483,
      "scientificName": "Oenanthe Vieillot, 1816",
      "canonicalName": "Oenanthe",
      "rank": "GENUS",
      "status": "ACCEPTED",
      "confidence": 24,
      "note": "Similarity: name=75; authorship=0; classification=-52; rank=0; status=1",
      "matchType": "FUZZY",
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Passeriformes",
      "family": "Muscicapidae",
      "genus": "Oenanthe",
      "kingdomKey": 1,
      "phylumKey": 44,
      "classKey": 212,
      "orderKey": 729,
      "familyKey": 9322,
      "genusKey": 2492483,
      "synonym": false,
      "class": "Aves"
    },
    {
      "usageKey": 7984973,
      "acceptedUsageKey": 2492483,
      "scientificName": "Oenanthe Pallas, 1771",
      "canonicalName": "Oenanthe",
      "rank": "GENUS",
      "status": "SYNONYM",
      "confidence": 23,
      "note": "Similarity: name=75; authorship=0; classification=-52; rank=0; status=0",
      "matchType": "FUZZY",
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Passeriformes",
      "family": "Muscicapidae",
      "genus": "Oenanthe",
      "kingdomKey": 1,
      "phylumKey": 44,
      "classKey": 212,
      "orderKey": 729,
      "familyKey": 9322,
      "genusKey": 2492483,
      "synonym": true,
      "class": "Aves"
    }
  ],
  "kingdom": "Plantae",
  "phylum": "Tracheophyta",
  "order": "Apiales",
  "family": "Apiaceae",
  "genus": "Oenanthe",
  "kingdomKey": 6,
  "phylumKey": 7707728,
  "classKey": 220,
  "orderKey": 1351,
  "familyKey": 6720,
  "genusKey": 3034893,
  "synonym": false,
  "class": "Magnoliopsida"
}
```


## 相关接口
	* /species/match
		+ Method：GET
		+ 描述：果提供了分类并且strict未设置为true，那么如果仅为name参数找不到直接匹配，则默认匹配也会尝试与之匹配。
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/match?verbose=true&kingdom=Plantae&name=Oenante>

```
{
  "usageKey": 3034893,
  "scientificName": "Oenanthe L.",
  "canonicalName": "Oenanthe",
  "rank": "GENUS",
  "status": "ACCEPTED",
  "confidence": 85,
  "note": "Similarity: name=75; authorship=0; classification=4; rank=0; status=1; nextMatch=5",
  "matchType": "FUZZY",
  "alternatives": [
    {
      "usageKey": 2492483,
      "scientificName": "Oenanthe Vieillot, 1816",
      "canonicalName": "Oenanthe",
      "rank": "GENUS",
      "status": "ACCEPTED",
      "confidence": 24,
      "note": "Similarity: name=75; authorship=0; classification=-52; rank=0; status=1",
      "matchType": "FUZZY",
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Passeriformes",
      "family": "Muscicapidae",
      "genus": "Oenanthe",
      "kingdomKey": 1,
      "phylumKey": 44,
      "classKey": 212,
      "orderKey": 729,
      "familyKey": 9322,
      "genusKey": 2492483,
      "synonym": false,
      "class": "Aves"
    },
    {
      "usageKey": 7984973,
      "acceptedUsageKey": 2492483,
      "scientificName": "Oenanthe Pallas, 1771",
      "canonicalName": "Oenanthe",
      "rank": "GENUS",
      "status": "SYNONYM",
      "confidence": 23,
      "note": "Similarity: name=75; authorship=0; classification=-52; rank=0; status=0",
      "matchType": "FUZZY",
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Passeriformes",
      "family": "Muscicapidae",
      "genus": "Oenanthe",
      "kingdomKey": 1,
      "phylumKey": 44,
      "classKey": 212,
      "orderKey": 729,
      "familyKey": 9322,
      "genusKey": 2492483,
      "synonym": true,
      "class": "Aves"
    }
  ],
  "kingdom": "Plantae",
  "phylum": "Tracheophyta",
  "order": "Apiales",
  "family": "Apiaceae",
  "genus": "Oenanthe",
  "kingdomKey": 6,
  "phylumKey": 7707728,
  "classKey": 220,
  "orderKey": 1351,
  "familyKey": 6720,
  "genusKey": 3034893,
  "synonym": false,
  "class": "Magnoliopsida"
}
```


## 相关接口
	* /species/search
		+ Method：GET
		+ 描述：名称用法全文搜索，涵盖所有或部分清单中所有名称用法的科学名称和方言名称、物种描述、分布和整个分类。结果按相关性排序，因为此搜索通常会返回大量结果。
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/search?q=Puma&rank=GENUS>

```
{
  "offset": 0,
  "limit": 20,
  "endOfRecords": false,
  "count": 100,
  "results": [
    {
      "key": 147439404,
      "nameKey": 9541873,
      "datasetKey": "db2ac0a4-e09a-4680-ab00-be20fb2c814c",
      "nubKey": 2435098,
      "parentKey": 147439403,
      "parent": "Felidae",
      "kingdom": "Animalia",
      "phylum": "Chordata",
      "order": "Carnivora",
      "family": "Felidae",
      "genus": "Puma",
      "kingdomKey": 147439348,
      "phylumKey": 147439350,
      "classKey": 147439352,
      "orderKey": 147439394,
      "familyKey": 147439403,
      "genusKey": 147439404,
      "scientificName": "Puma",
      "canonicalName": "Puma",
      "authorship": "",
      "nameType": "SCIENTIFIC",
      "taxonomicStatus": "ACCEPTED",
      "rank": "GENUS",
      "origin": "DENORMED_CLASSIFICATION",
      "numDescendants": 2,
      "numOccurrences": 0,
      "habitats": [],
      "nomenclaturalStatus": [],
      "threatStatuses": [],
      "descriptions": [],
      "vernacularNames": [],
      "synonym": false,
      "higherClassificationMap": {
        "147439348": "Animalia",
        "147439350": "Chordata",
        "147439352": "Mammalia",
        "147439394": "Carnivora",
        "147439403": "Felidae"
      },
      "class": "Mammalia"
    }
  ]
}
```


## 相关接口
	* /species/suggest
		+ Method：GET
		+ 描述：一个快速简单的自动完成服务，通过对学名进行前缀匹配，最多返回20个名称用法。结果按相关性排序。
		+ 是否换页：是
		+ 参数：language
		+ 接口示例：<https://api.gbif.org/v1/species/suggest?datasetKey=d7dddbf4-2cf0-4f39-9b2a-bb099caae36c&q=Puma%20con>

```
[
  {
    "key": 2435099,
    "nameKey": 9541887,
    "kingdom": "Animalia",
    "phylum": "Chordata",
    "order": "Carnivora",
    "family": "Felidae",
    "genus": "Puma",
    "species": "Puma concolor",
    "kingdomKey": 1,
    "phylumKey": 44,
    "classKey": 359,
    "orderKey": 732,
    "familyKey": 9703,
    "genusKey": 2435098,
    "speciesKey": 2435099,
    "parent": "Puma",
    "parentKey": 2435098,
    "nubKey": 2435099,
    "scientificName": "Puma concolor (Linnaeus, 1771)",
    "canonicalName": "Puma concolor",
    "rank": "SPECIES",
    "status": "ACCEPTED",
    "synonym": false,
    "higherClassificationMap": {
      "1": "Animalia",
      "44": "Chordata",
      "359": "Mammalia",
      "732": "Carnivora",
      "9703": "Felidae",
      "2435098": "Puma"
    },
    "class": "Mammalia"
  }
 ]
}
```