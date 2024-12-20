# News Article Generator (from pool of existing newspapers)

This is to demo how can you utilise Bedrock knowledge base feature for content generation using upon your own corpus data.

You can bring your own data OR for basic tests, you can refer the files uploaded in "DummyData" folder and can put the PDFs in your S3 bucket.

### Part 1. Deploy knowledge base in your environemnt :
You can follow the steps mentioned on this [page]([url](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/rag/knowledge-bases/features-examples/04-infrastructure/e2e-rag-using-bedrock-kb-cfn
)) and run the Cloudformation templates to setup a knowledge base in your enviornment.

### Part 2. You can upload and test these sample news papers ([1]([url](https://github.com/user-attachments/files/18177754/FE.Delhi.07.Nov.2024.pdf)),[2]([url](https://github.com/user-attachments/files/18177752/DC_Hyderabad_02-11-2024.pdf)),[3]([url](https://github.com/user-attachments/files/18177749/Asian.Age.Delhi.19.Nov.2024.pdf))) in your S3 bucket. Sync the data source and start testing with prompts like below :

I've tested with several models and putting screen-shots of respones from Nova Lite 1.0 :

"What all news you have releted to recent air pollution incidents ?"
![image](https://github.com/user-attachments/assets/d1a9dbbc-6dd4-4904-9ec5-b99459ea57da)

"Write an article on US presidential elections with a catchy viral heading."
<img width="306" alt="Screenshot 2024-12-20 at 4 44 11 PM" src="https://github.com/user-attachments/assets/9cb212f9-902a-4453-aed8-f5dfc9c3a3db" />

You can further tweak the prompts and get respective contents generated.


[FE Delhi 07 Nov 2024.pdf](https://github.com/user-attachments/files/18177754/FE.Delhi.07.Nov.2024.pdf)
[DC_Hyderabad_02-11-2024.pdf](https://github.com/user-attachments/files/18177752/DC_Hyderabad_02-11-2024.pdf)
[Asian Age Delhi 19 Nov 2024.pdf](https://github.com/user-attachments/files/18177749/Asian.Age.Delhi.19.Nov.2024.pdf)
