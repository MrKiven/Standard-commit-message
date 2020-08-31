我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# Standard-commit-message
:sunny: Generic standard of a commit message


## The seven rules of a greate git commit message

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain *what* and *why* vs. *how*

## Something else

Subject include three fields: `type(Y)`, `scope(N)`, `subject(Y)`

`tyepe` use to explain type of this commit, include seven Identifications:
    
    * Feature
    * Fix
    * Docs
    * Style
    * Refactor
    * Test
    * Chore

**Example**

    <type>(<scope>): <subject>
    // blank line
    <body>
    // blank line
    <footer>

**NOTE**

    footer part is only used in two cases:
        
      - Breaking change
        
        *Breaking change: Some explain*
          
      - Close issue

**EXAMPLE**

```
Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first lie is treated as the
subject of commit and the rest of the text as the body. The blank
line separating the summary from the body is critical (unless you
omit the body entirely); various tools like `log`, `shortlog` and
`rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker or has breaking change, put references
to them at the bottom, like this:

Resolves: #123
See also: #456
Breaking changes: something changed
```


## LICENSE

[MIT](LICENSE)
