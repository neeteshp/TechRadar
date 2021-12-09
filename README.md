# TechRadar

Inspired from [ThoughtWorks](https://www.thoughtworks.com/radar) TechRadar, this TechRadar is further enhancement of the one published by [Zalando](https://github.com/zalando/tech-radar).

Make changes as per your need in [index.html](https://github.com/neeteshp/TechRadar/blob/master/index.html) and [data.csv](https://github.com/neeteshp/TechRadar/blob/master/data.csv) file

## index.html

```js
quadrant: ['Languages', 'Infrastructure', 'Datastores', 'Data Management'].indexOf(row.quadrant),
```

```js
quadrants: [
					{ name: "Languages" },
					{ name: "Infrastructure" },
					{ name: "Datastores" },
					{ name: "Data Management" },
				],
```
## data.csv

```csv
name,ring,quadrant,moved,link
Java,ADOPT,Languages,none,../docs/java.html
Typescript,TRIAL,Languages,down,../docs/typescript.html
.Net,ASSESS,Languages,up,../docs/typescript.html
AWS CloudFormation,TRIAL,Infrastructure,up,https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html
AWS DynamoDB,HOLD,Datastores,up,https://aws.amazon.com/dynamodb/
Kafka,ASSESS,Data Management,down,https://kafka.apache.org/
```

## Live Demo
[https://neeteshp.github.io/TechRadar/](https://neeteshp.github.io/TechRadar/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
