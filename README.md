# myactions
Git actions.
Django Pyblog 🚁
Django blog - ElasticSearch + MySQL + Redis 🚀

Why?
Most of us use wordpress 🥱 for blogs (so do I: https://pyblog.xyz). The search operation in wordpress takes forever, because it's a simple column like '%<complete input string>% 🤕
To perform faster search operations on tags, categories and other key-words. While it can be achieved with Relational and other NoSQL data stores, Elastic Search is the best when it comes to SEARCH 😎
Installation ElasticSearch (MacOS)
Tap the Elastic Homebrew repository: brew tap elastic/tap
brew install elastic/tap/elasticsearch-full
pip install elasticsearch-dsl
Start the Server
cd /usr/local/var/homebrew/linked/elasticsearch-full/bin
./elasticsearch To start ES from GUI, follow: https://opensource.com/article/19/7/installing-elasticsearch-macos
Test ES Set-up
