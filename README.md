# scikitlearn-to-sagemaker

Setup and run instructions:
- Open the AWS Console
- Go to SageMaker
- From the menu on the left, please choose "Studio" (Not studio lab)
- Create a new user
- Launch a new studio (by pressing "Open Studio" next to the user/role)
- Upload the Jupyter Notebook and Dataset to the IDE.
- Run the cells

At this point, we have deployed an endoint that we can use for inference!

You can check it by going to:
SageMaker -> Inference -> Endpoints


We can use the API like so
https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_runtime_InvokeEndpoint.html

With Tableau (might worth consiering QuickSight instead)
https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm




