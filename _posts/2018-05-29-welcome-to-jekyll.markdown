---
layout: post
title:  "Jekyll 博客更新办法"
date:   2018-05-29 18:05:55 +0300
image:  11.jpg
tags:   [工具]
---

## 博客命令步骤指南

- 定位：cd…   

- 查看状态： git status   

- 添加修改：

git add .
 
git commit -m "description"
 
或者直接输入`git commit -am "Add file"`

- 推送：git push

- 运行预览：bundle exec jekyll serve  或者 `jekyll serve`


博客文件放在 `_posts`当中


添加文件名称：

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

代码：

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
