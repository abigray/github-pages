# Blog and Portfolio 

## Built from Suze Shardlow's GitHub Pages Workshop

Install Ruby, Jekyll and Bundle on an EC2 instance.

```
$ git clone https://github.com/SuzeShardlow/github-pages-workshop.git
$ cd github-pages-workshop
$ bundle install
$ bundle exec jekyll serve --watch --port 8081 - --host 0.0.0.0
```

Then browse to `http://<<ec2 ip>>:8081/github-pages/`.
