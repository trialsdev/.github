# Clinical Trial Migration Toolbox

## Overview

The primary purpose of this toolbox is to introduce clinical trial imagers to cloud computing resources that can assist in making their work more efficient and effective. Imaging in clinical trials is acted upon at the local trial site and historically gathered for review in a delayed fashion, either through the transport of files on encrypted physical media or via proprietary electronic data capture (EDC) software to a central archival database. The software and systems used to store, de-identify, review and annotate imaging data at trial sites can vary widely, as can the methods of transport and archival storage solutions. As machine learning (ML) algorithms increasingly assist in the classification of images and quantification of biomarkers, they become indispensable to investigators making decisions regarding trial eligibility, treatment, safety and imaging-based outcomes. Therefore, safe and effective processing of clinical trial images is of more importance than ever. 

## Software Used

We chose to use the <a href = "https://cloud.google.com/">Google Cloud Platform (GCP)</a> as our cloud computing provider based on prior experience, although other cloud computing providers can utilize <a href = "https://registry.terraform.io/providers/hashicorp/google/latest/docs">Terraform</a> code and we hope in the future to make available similar cloud architectures for other cloud platforms. After a proper setup with a few lines of code cloud architectures that automate key processes in clinical trial imaging can be tested. Our hope is that this toolbox stimulates collaboration and sharing of cloud computing resources for clinical trial imaging. 

## Core Processes

We have currently used GCP and terraform to demonstrate four core processes.

1. <a href = "https://github.com/trialsdev/Biomarker-Segmentation-Tutorial">Biomarker Segmentation</a>
2. <a href = "https://github.com/trialsdev/Biomarker-Classification-Tutorial">Biomarker Classification</a>
3. <a href = "https://github.com/trialsdev/GCP-Image-Viewer">Image Quality Assurance</a>
4. <a href = "">DeID Audit</a>

More workflows and GPC architectures will be developed and publicized in our GitHub repository in the future. 

