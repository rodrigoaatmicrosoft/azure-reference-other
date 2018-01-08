---
title: "Data Transformation | Microsoft Docs"
ms.custom: ""
ms.date: 10/05/2016
ms.reviewer: ""
ms.service: "machine-learning"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "reference"
ms.assetid: 9c2844b8-7a4c-483b-848a-e35a27855716
caps.latest.revision: 14
author: "jeannt"
ms.author: "jeannt"
manager: "jhubbard"
---
# Data Transformation
This article lists the modules provided in  Azure Machine Learning Studio for data transformation. For machine learning, "data transformation" entails some very general tasks, such as joining datasets or changing column names, but it also includes many tasks that are specific to machine learning, such as normalization, binning and grouping, inference of missing values, and so forth. 

> [!IMPORTANT]
> Data you use in Azure Machine Learning Studio is generally expected to be "tidy" before you import it to Studio. Such data preparation can include ensuring that the data uses the correct encoding, checking that the data has a consistent schema, and so forth. 
> 
> You can now use the Azure Machine Learning Workbench to transform and prepare all kinds of data. See [Data Transformations “By Example” in the Azure Machine Learning Workbench](https://blogs.technet.microsoft.com/machinelearning/2017/09/25/by-example-transformations-in-the-azure-machine-learning-workbench/)

Modules for data transformation are grouped into the following task-based categories:
   
-   [Creating filters for digital signal processing](data-transformation-filter.md): Digital signal filters can be applied to numeric data to support machine learning tasks such as image recognition, voice recognition, and waveform analysis.  
  
-   [Generating and using count-based features](data-transformation-learning-with-counts.md): Count-based featurization modules help you develop compact features for use in machine learning.  
  
-   [General data manipulation and preparation](data-transformation-manipulation.md): Merging datasets, cleaning missing values, grouping and summarizing data, changing column names and data types, or indicating which column is a label or feature.  
  
-   [Sampling and splitting datasets](data-transformation-sample-and-split.md): Divide your data intro training and test sets, split datasets by percentage or by a filter condition, or perform sampling.  
  
-   [Scaling and reducing data](data-transformation-scale-and-reduce.md): Prepare numerical data for analysis by applying normalization or by scaling. Bin data into groups, remove or replace outliers. perform principal component analysis (PCA).  
  
##  <a name="categories"></a> List of Modules  

The following table lists the Data Transformation categories. Click the link to see more about each category.  
  
|Category|  
|--------------|  
|[Data Transformation / Filter](data-transformation-filter.md)|  
|[Learning with Counts](data-transformation-learning-with-counts.md)|  
|[Data Transformation / Manipulation](data-transformation-manipulation.md)|  
|[Data Transformation / Sample and Split](data-transformation-sample-and-split.md)|  
|[Data Transformation / Scale and Reduce](data-transformation-scale-and-reduce.md)|  
  
## See Also  
 [Data Format Conversions](data-format-conversions.md)   
 [Data Input and Output](data-input-and-output.md)   
 [Feature Selection](feature-selection-modules.md)   
 [Module Categories and Descriptions](machine-learning-module-descriptions.md)