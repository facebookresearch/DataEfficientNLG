## Best Practices for Data-Efficient Modeling in NLG: How to Train Production-Ready Neural Models with Less Data

Code and dataset supporting the paper:

Ankit Arun, Soumya Batra, Vikas Bhardwaj, Ashwini Challa, Pinar Donmez, Peyman Heidari, Hakan Inan, Shashank Jain, Anuj Kumar, Shawn Mei, Karthik Mohan, Michael White† [Best Practices for Data-Efficient Modeling in NLG: How to Train Production-Ready Neural Models with Less Data](https://www.aclweb.org/anthology/2020.coling-industry.7/).

If you find this dataset useful in your research, please consider citing our paper.

## Reference

```
@inproceedings{arun-etal-2020-best,
    title = "Best Practices for Data-Efficient Modeling in {NLG}:How to Train Production-Ready Neural Models with Less Data",
    author = "Arun, Ankit  and
      Batra, Soumya  and
      Bhardwaj, Vikas  and
      Challa, Ashwini  and
      Donmez, Pinar  and
      Heidari, Peyman  and
      Inan, Hakan  and
      Jain, Shashank  and
      Kumar, Anuj  and
      Mei, Shawn  and
      Mohan, Karthik  and
      White, Michael",
    booktitle = "Proceedings of the 28th International Conference on Computational Linguistics: Industry Track",
    month = dec,
    year = "2020",
    address = "Online",
    publisher = "International Committee on Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.coling-industry.7",
    pages = "64--77",
}
```

## Data

Datasets for **Time**, **Alarm**, and **Reminder** domains is included.
**Weather** domain data can be found at: https://github.com/facebookresearch/TreeNLG .

Each response was collected by providing annotators, who are native English speakers, with a *user query*, and a *compositional meaning representation* (with discourse relations and dialog acts). All of these are made available in our dataset. See our linked paper for more details.

#### Data Statistics

Dataset           | Train | Val  | Test
-------           | ----- | ---  | ----
Time              | 20578 | 5800 | 2940
Alarm             | 1410  | 365  | 202
Reminder          | 9717  | 2794 | 1397

### License

TreeNLG is released under [CC-BY-NC-4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode), see [LICENSE](LICENSE.md) for details.
