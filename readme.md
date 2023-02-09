first command to create the env 
```bash
python3.9 venv -m your_prefered_name
```
then create the `requirement_dev.txt` file

```txt
requests=2.27.1
boto3=1.24.2
pandas=1.4.2
pyarrow=8.0.0
fsspec=2022.5.0
s3fs<=0.4
```

then create a requirements.txt

here we have to remove the boto3 because when we deploy to aws lamda it already have it installed

```
requests=2.27.1
pandas=1.4.2
pyarrow=8.0.0
fsspec=2022.5.0
s3fs<=0.4
```

setup your aws account

let's create a s3 bucket

```aws
aws s3 mb s3://awslamdaghactivity
```

then run this command to verify your s3 has been created

```
aws s3 ls
```

now let's remove this bucker

```
aws s3 rm s3://awslamdaghactivity
```
then run this command to verify your s3 has been deleted

```
aws s3 ls
```

setup notebooks 


```

```

```

```

```

```