# interview_humanssum

This repository contains the data and source code used for the paper titled "Speech vs. Transcript: Does It Matter for Human Annotators in Speech Summarization?" that was accepted at ACL 2024. 

Humans can summarize speech when it is presented by (a) listening to the speech directly and then constructing the summary based on this, or (b) reading a textual transcript of the content spoken in the recording, and using that to construct the summary. It is unclear whether summaries based on listening to audio differ from summaries based on reading transcripts. 

Our paper considers the impact of the source modality (speech versus manual transcript versus automatic transcript) and expertise of the annotator. 

The data was collected using third-party expert annotators through our team from ASAPP Inc., and through non-expert annotators from the Amazon Mechanical Turk Platform. 

## Repository Organization 

---> code - Contains Jupyter notebooks that can be used to obtain the numbers reported in the paper. The code requires installation of UniEval and BARTScore in the root directory of this repository. 
---> data - Contains data used for this project including audio URLs and transcripts from the NPR website and our human annotated summaries. 


## LICENSE Information 

This data can be used subject to the terms of an Apache LICENSE 2.0. However, the NPR data can be used subject to their license terms only. 
The links to NPR content within this repository does not imply any endorsement or promotion of the material. 

## Citation


If you use the data, code or research observations from this repository, please cite our paper. 


