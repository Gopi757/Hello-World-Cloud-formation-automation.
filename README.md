#Introduction 

Created the infrastructure to host a ‘Hello World’ application using CloudFormation.

#Prequisites:

Aws IAM user with EC2,cloudformation,VPC read and write polcies.

#Installation and Configuration.

Use  Hello-world.yml for creation of stack.

In created stack dashboard select template is ready option and uploaded file from my local in the format of Hello-World.yml file.

I specified the stack details by using stack name as Hello-World and Parameters.

We need to review the Configured Stack Options and should be specify the tag name.

Once we done with review we can click on create stack then we can see that Hello-world stack status CREATE_IN_PROGRESS state.

we can notice that Hello-world stack is created and status changed to CREATE_COMPLETE.

We can see that output as a Hello-World by visiting the DNS of the instance.
