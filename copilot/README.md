# AWS Copilot

Simple example with AWS copilot

## Download & Configure AWS Copilot


```bash
curl -Lo copilot https://github.com/aws/copilot-cli/releases/latest/download/copilot-linux && chmod +x copilot && sudo mv copilot /usr/local/bin/copilot && copilot --help
aws configure
```

## Usage

```bash
git clone https://github.com/aws-samples/aws-copilot-sample-service example; cd example

# Answer a few questions and Deploy your service
copilot init

```

## Clean up
```bash
copilot app delete
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
