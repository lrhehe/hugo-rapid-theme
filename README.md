# hugo-rapid-theme

fork from [http://blog.coderzh.com/](http://blog.coderzh.com/) 

some changes：

1. show two columns for all pages, fix a related bug
2. show ditail when show post list items, at most show 10 items
3. enlarge author avatar
4. config twitter，github，weibo account in config.yaml​

Demo: [http://blog.lrhehe.com/](http://blog.lrhehe.com/)

## Step1 Install Hugo

See [Hugo Install](http://www.gohugo.org/doc/overview/installing/)

## Step2 Create your site

```
hugo new site your-blog-name
cd your-blog-name
```

## Step3 Clone the theme repo

```
git clone https://github.com/lrhehe/hugo-rapid-theme.git themes/hugo-rapid-theme

# replace config file
rm config.toml
cp themes/hugo-rapid-theme/config.yaml .
```

## Step4 Start your site

```
# new content
hugo new about.md
# start server
hugo server
```

## Step5 Have Fun

Now you can open [http://localhost:1313](http://localhost:1313)

Modify the config.yaml and other things, and have fun!

You can also make this repo as submodule:

```
git init
git submodule add https://github.com/lrhehe/hugo-rapid-theme.git themes/hugo-rapid-theme
```