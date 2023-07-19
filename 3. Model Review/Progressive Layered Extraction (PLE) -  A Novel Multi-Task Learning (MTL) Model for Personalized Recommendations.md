
- notion link : https://www.notion.so/dasomkang/Progressive-Layered-Extraction-PLE-A-Novel-Multi-Task-Learning-MTL-Model-for-Personalized-Recom-0a12fcaf35d6412da713f8e9419dffdb


### Progressive Layered Extraction (PLE): A Novel Multi-Task Learning (MTL) Model for Personalized Recommendations

-   Keywords
    -   Multi-task Learning, Recommender System, Seesaw Phenomenon
-   Abstract
    
    -   Multi-task learning(MTL) has been successfully applied to many recommendation applications
    -   often suffer from performance degeneration with
        -   **negative transfer** due to the complex and competing task correlation in real-world recommender system.
        -   **seesaw phenomenon** that performance of one task is often improved by hurting the performance of some other tasks.
    -   To address these issues, propose a **Progressive Layered Extraction (PLE) model** with a novel sharing structure design.
    -   PLE
        -   seperates shared components and task-specific components explicitly
        -   adopts a progressive routing mechanism to extract and seperate deeper semantic knowledge gradually
        -   improving efficiency of joint representation learning and information routing across tasks in a general setup.
    -   experiments
        -   dataset : Tencent video recommendation dataset with 1 billion sample(real-world data)
        -   apply PLE to
            -   complicated correlated tasks
                -   two-task cases
                -   multi-task cases
            -   normally correlated tasks
                -   two-task cases
                -   multi-task cases
        -   results
            -   PLE outperforms SOTA MTL models significantly under different task correlations and task-group size.
            -   online evaluation of PLE on a large-scale content recommendation platform at Tencent manifests 2.23% increase in view-count, 1.84% increase in watch time compared to SOTA MTL models
            -   offline experiments on publick benchmark datasets
                -   PLE can be applied to a variety of scenarios besides recommendation to eliminate the seesaw phenomenon.
    -   PLE now has been deployed to the online video recommender system in Tencent successfully.