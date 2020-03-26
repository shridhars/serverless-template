# Cookiecutter SAM for Python Lambda functions

This is a custome template for Cactus communication created with reference from [Cookiecutter](https://github.com/audreyr/cookiecutter) template to create a Serverless App based on Serverless Application Model (SAM) and Python 3.6.

It is important to note that you should not try to `git clone` this project but use `cookiecutter` CLI instead as ``{{cookiecutter.project_slug}}`` will be rendered based on your input and therefore all variables and files will be rendered properly.

## Requirements

[Install docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
[Install sam cli for ubuntu](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install-linux.html
) 

## Usage

Generate a new SAM based Serverless App: `sam init --location git+ssh://git@github.com/cactuscommunications/serverless-template.git`. 

You'll be prompted a few questions to help this custom template to scaffold this project and after its completed you should see a new folder at your current path with the name of the project you gave as input.

## Options


Option | Description
------------------------------------------------- | ---------------------------------------------------------------------------------
`include_apigw` | Includes sample code for API Gateway Proxy integration for Lambda and a Catch All method in SAM as a starting point

# Credits

* This project has been generated with [Cookiecutter](https://github.com/audreyr/cookiecutter)
* [Bruno Alla's Lambda function template](https://github.com/browniebroke/cookiecutter-lambda-function)


License
-------

This project is licensed under the terms of the [MIT License with no attribution](/LICENSE)
