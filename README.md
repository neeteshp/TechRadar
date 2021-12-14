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
MIT License

Copyright (c) [2021] [Neetesh Pratap Singh]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
