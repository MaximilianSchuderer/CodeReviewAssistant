# **AI-Codereview-Pipeline installation guide**

**Azure-Devops:**

Copy .yml pipeline in the root of your repository

![image](https://github.com/user-attachments/assets/6d72cd9c-de2e-4371-8936-05cd1d200ace)
<p>&nbsp;</p>
<p>&nbsp;</p>
Preparing the Azure DevOps project to allow pipelines to contribute to pull requests

Go to "Project settings > Repositories

![image](https://github.com/user-attachments/assets/6d362424-438d-4a58-9b65-c9ee6340901e)

![image](https://github.com/user-attachments/assets/f142707b-d814-469e-96a1-bbdea68e5e94)
<p>&nbsp;</p>
<p>&nbsp;</p>
Select your repository and go to "Security" and allow to the build service "Contribute" and "Contribute to pull requests" 

![image](https://github.com/user-attachments/assets/a60092d3-6291-4618-85ed-1d9c63aa9c04)

![image](https://github.com/user-attachments/assets/57711559-62f7-477e-bc2a-50e59491cddc)
<p>&nbsp;</p>
<p>&nbsp;</p>
After that go to "Pipelines" and click on "Create Pipeline" and add the previously added .yml pipeline

![image](https://github.com/user-attachments/assets/11794133-0ca5-4921-b88a-e7e813895b68)

![image](https://github.com/user-attachments/assets/6f6d5dda-c26f-4a78-81a7-425cb57dcac8)

![image](https://github.com/user-attachments/assets/0998e7f2-a3b9-4f55-87b5-22bbbfd59ab2)

![image](https://github.com/user-attachments/assets/7ef834fe-2617-4a7f-ac1b-579379757df4)
<p>&nbsp;</p>
<p>&nbsp;</p>
Once done go to "Repositories > Branches" and select "Branch policies" in the context menu of your target branch

![Screenshot from 2025-02-08 19-29-55](https://github.com/user-attachments/assets/e145fa60-aa4c-4539-8abc-7f54262b72e7)
<p>&nbsp;</p>
<p>&nbsp;</p>
Click the add button on "Build Validation" to configure your AI-Codereview pipeline to run with each PR agains the target branch

![image](https://github.com/user-attachments/assets/0f62f8ce-d82e-4b93-9062-254962f88dcd)

![image](https://github.com/user-attachments/assets/2b21934d-2e1b-4106-b889-f19c9d35a171)
<p>&nbsp;</p>
<p>&nbsp;</p>
After that the pipeline does an code review of each commit in your pr and add comments to your code changes

![image](https://github.com/user-attachments/assets/2373e9d4-4cb3-4ceb-8054-76a6809b09a0)

![image](https://github.com/user-attachments/assets/b88b98fc-365a-4e04-bc79-4f5f3e474cb7)

![image](https://github.com/user-attachments/assets/031021d2-2c2b-4f64-9c91-504071dee4f9)





