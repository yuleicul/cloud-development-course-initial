# Task 1 (Cloud Introduction)

## Application Functionality (**MUST HAVE**)

---

By the end of the program your application must be able to do:

1. Products representation on Home page should be based on product-service API.
2. Products are still static, but products are hardcoded on BE product-service.
3. Product images are not randomly generated on client side. Product image as well as another product model information should be stored on BE side in RDS.
4. Products can be created through CSV product file import from client side.
5. Cart can be created with an appropriate product set.
6. Auth logic should be in place

## Tasks

---

### Task 1.1

1. Install Discord (or go to its web version)
2. Register a new account if you don't have one and [join the course chat](https://discord.com/invite/ATsHAqCsnw)
3. Register in [RS App](https://app.rs.school/registry/student?course=aws-2021)
  
    - Feel free to ask any questions in our Discord chat

### Task 1.2

1. Revise:

    - What is REST; what are the main principles of it.
    - How to create a basic REST API service using Express.

2. Read about (if you would like to learn beyond the curriculum):

    - On-Premise architecture

    - Cloud Architecture

      > Cloud computing is the on-demand delivery of compute power, database, storage, applications, and other IT resources through a cloud services platform through the internet with pay-as-you-go pricing. Traditionally, a developer looking to build an application had to procure, set up, and maintain physical infrastructure and the application. This is where cloud computing comes in.
      >
      > --- [Cloud essentials](https://aws.amazon.com/getting-started/cloud-essentials/)

    - Cloud benefits

      > 1. Pay as you go
      > 2. Benefit from massive economies of scale
      > 3. Stop guessing capacity
      > 4. Increase speed and agility
      > 5. Realize cost savings
      > 6. Go global in minutes
      >
      > --- [Cloud essentials](https://aws.amazon.com/getting-started/cloud-essentials/)

    - What do the region, availability zone, IAM mean?

      > A Region is a physical location in the world where we have multiple Availability Zones. 
      >
      > Availability Zones consist of one or more discrete data centers, each with redundant power, networking, and connectivity, housed in separate facilities.
      >
      > --- [Cloud essentials](https://aws.amazon.com/getting-started/cloud-essentials/)
      >
      > IAM, AWS Identity and Access Management, is a web service that helps you securely control access to AWS resources. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.
      >
      > --- [What is IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

    - How to use cloud solutions (Read about possible showcases)?

    - What is a serverless architecture?

3.  Pass the [test](https://forms.gle/RHBM9HBoSKzumT9v9)

    - You will be able to pass only once!
    
      > Q: Is it true that newly created users don't have any permissions by default and they require admins to explicitly assign the necessary permissions?
      >
      > A: Yes (why??)

### Task 1.3

1. Decide which FE framework will be used:

    - [React Front app](https://github.com/EPAM-JS-Competency-center/shop-react-redux-cloudfront).
    - [Angular Front app](https://github.com/EPAM-JS-Competency-center/shop-angular-cloudfront).
    - [Vue Front app](https://github.com/EPAM-JS-Competency-center/shop-vue-vuex-cloudfront).

2. Clone the selected repo, install dependencies, run the app and check if everything is okay

    - Check `package.json` and/or `README.md` for additional details.

      > Attention that use `nvm` to degrade node version to `14`, in case of version errors.

3. Since you're going to be building an E-Commerce solution, decide which commodities will be sold in your shop.

    - Mixed, Games, Toys, Electronic devices, etc - you name it!

### Task 1.4

> Follow [Creating your first IAM admin user and user group](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html) to finish the 1st&2ed task.
>
> Follow [Installing or updating the latest version of the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) for Linux and [Configuration basics](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html) to finish the 3rd task.

1. Register in AWS following best practices.

    - Do be careful with your root credentials and make sure to protect it properly.

2. Create an IAM user and assign AdministratorAccess policy to it.

3. Using CLI, connect to your AWS account and get the created IAM user information

    - Do remember about AWS credentials setup on your local machine

      > Forgot to download the .csv file. ID and Key are stored in `wandering-mind` logs.

    - Command example that needs to work from your terminal: `aws iam get-user --user-name=MyUser`

4. Wait for the next task to be announced and help others in the chat if they have any issues
