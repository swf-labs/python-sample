## Openshift Django Sample

Getting Started with Docker using Python.


### Local development

To run this project in your development machine, follow these steps:

1. Fork this repo and clone your fork:

  `git clone https://github.com/chriskretler/openshift-python-sample.git`

2. Build the docker image:

  `docker build -t python-sample .`

3. Run the docker image:

  `docker run -it -p 8080:8080 python-sample`

4. Open your browser and go to http://127.0.0.1:8080, you will be greeted with a welcome page.