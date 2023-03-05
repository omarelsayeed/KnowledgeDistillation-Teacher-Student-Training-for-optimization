# KnowledgeDistillation-Teacher-Student-Training-for-optimization

## Distilling the knowledge in a network.

##### a fairly old approach that's used to utilize pretrained models in vision and speech recognition to train a smaller models with a better performance.

##### The idea is to combine the loss function from the task itself (cross entropy or ctc) and the large model(aka teacher)'s output (logits) but not directly , we use softlabels for the teacher.

##### with this combined loss you can train the student faster & get better results .

![1_DdClMPqhErordaun8Dw14Q](https://user-images.githubusercontent.com/64399795/222950410-8f2e7ceb-7aec-4eae-8eff-f6f3e764cfc7.png)
![Comparison-between-standard-Knowledge-Distillation-a-and-our-pipeline-b](https://user-images.githubusercontent.com/64399795/222950425-5687bdfd-b832-4f17-af2e-4661ccdbabe4.png)
![image](https://user-images.githubusercontent.com/64399795/222950465-d3f43ff3-38ed-47d3-8f03-ce85c83b47fc.png)
