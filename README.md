# tf_rnn_model_load_testing

### How it works?

create virtual environment using:

```shell
virtualenv <env_name>
```
Change the directory.
```shell
cd <env_name>
```
Clone this repository.
```shell
git clone https://github.com/chaturvediabhay24/pytorch_cnn_model_load_testing.git
```
Change the directory.
```shell
cd pytorch_cnn_model_load_testing
```
Install dependencies.
```shell
pip install -r requirements.txt
```
Run these two command parallely in two different shells.
```shell
python app.py
```
```shell
locust
```

## View
* For viewing api open http://127.0.0.1:5000
* For viewing locust ui open http://localhost:8089
* Enter the number of users, hatch rate and host(http://127.0.0.1:5000) to start the test.
