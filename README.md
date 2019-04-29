# QWIKLab Instructions

Welcome to Apache MXNet Bootcamp. We will use Amazon SageMaker to run the Apache MXNet lab sessions.

1.	Go to [https://events-aws.qwiklabs.com/](https://events-aws.qwiklabs.com/) and create an account.

2.	Send the email-id, with which you registered in qwiklabs, to **wamy@amazon.com**  
 (Your QWIKLab account will be added to the student list in the lab. This will essential to get access to the lab.)
3.	Once you login to QwikLabs, click on the MXNet/Gluon BootCamp Lab
    ![Qwiklabs Gluon Lab](./assets/qwiklabs_workshop_home.png)

4. Once inside the lab, use the Notebook Instance and the credentials (Account ID, User Name, Password) provided to login to Amazon SageMaker jupyter notebook.
    ![Qwiklabs Sage Maker](./assets/qwiklabs_workshop_sagemaker.png)

5. We will download the lab material to use on the notebook, start a new terminal session on SageMaker.
    ![Qwiklabs Sage Maker Terminal](./assets/qwiklabs_workshop_sagemaker_terminal.png)

6. Clone the github repo.
    ```
    git clone https://github.com/nswamy/deeplearning-workshop ~/SageMaker/deeplearning-workshop
    ```

7. Now we can access the material from the notebook instance and run through the exercises by going into the `deeplearning-workshop` directory.

8. Choose mxnet_p36 conda environment as the Kernel when executing a notebook.
![Qwiklabs Sage Maker Conda Env](./assets/qwiklabs_workshop_sagemaker_condaenv.png)

You are all set! Let's get started...