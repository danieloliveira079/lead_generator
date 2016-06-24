# Lead Generator

Create unlimited leads cvs

###Usage

Build the docker image and start the container

`docker build -t lead-generator .
docker run -it --rm  -v $PWD:/src/app -w /src/app lead-generator bash`

Generate fake leads

`faked_csv -i rds_lead.csv.json -o lead200.csv`

###References
[https://github.com/jiananlu/faked_csv](https://github.com/jiananlu/faked_csv)
