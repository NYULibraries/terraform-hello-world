Install terraform:

```
brew install terraform
```

Enter either subdirectory and initialize terraform:

```
cd single-instance
terraform init
```

View what terraform will create/modify/destroy:

```
terraform plan
```

Apply changes via API (with environment variables `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` set):

```
terraform apply
```

Output graph of dependencies (viewable via [Graphviz](http://www.webgraphviz.com/)):

```
terraform graph
```
