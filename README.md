# Travel Insurance Claim Prediction
Travel Insurance Hackathon

Team: Wanderlust Data

Organization: Greyatom Hackathon

Contributors: [Ashreet Sangotra](https://github.com/ashreetsangotra), [Niyati Bhayani](https://github.com/niyati-bhayani), [Samira Nigrel](https://github.com/samira-nigrel) and [Manthan Gandhi](https://github.com/manthangandhi)

![](https://www.acko.com/wp-content/uploads/2018/12/How-to-claim-travel-insurance-1024x683.jpg)



## Problem Description

Insurance companies take risks over customers. Risk management is a very important aspect of the insurance industry. Insurers consider every quantifiable factor to develop profiles of high and low insurance risks. Insurers collect vast amounts of information about policyholders and analyze the data.

As a Data scientist in an insurance company, you need to analyze the available data and predict whether to sanction the insurance or not.

## Dataset Description

A zipped file containing train, test and sample submission files are given. The training dataset consists of data corresponding to 52310 customers and the test dataset consists of 22421 customers. Following are the features of the dataset

- Target: Claim Status (Claim)
- Name of agency (Agency)
- Type of travel insurance agencies (Agency.Type)
- Distribution channel of travel insurance agencies (Distribution.Channel)
- Name of the travel insurance products (Product.Name)
- Duration of travel (Duration)
- Destination of travel (Destination)
- Amount of sales of travel insurance policies (Net.Sales)
- The commission received for travel insurance agency (Commission)
- Age of insured (Age)
- The identification record of every observation (ID)

## Evaluation Metric

The evaluation metric for this task will be `precision_score`. Read up about it more [here](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html).

## Submission Format

The user has to submit a csv file with the ID and Claim label. Sample submission file has been given to you. You can refer the sample submission file.
