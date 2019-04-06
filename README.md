# Blogger Foo Bar Personal Website Repo (Content)

Its a repo of Blogger _Foo Bar_ personal website repo. He likes to share his website content
with world.

# How to get your own blogging website

1. Clone it
  ```
  git clone https://github.com/bloggerfoobar/bloggerfoobar.github.io myblog
  ```
3. Enter into the directory
  ```
  cd myblog
  ```
3. Replace content of pages like _About_ or blog posts.
4. Commit your changes
5. Create GitHub repo as `<your-github-username>.github.io`
6. Remove existing `origin`
  ```
  git remote remove origin
  ```

7. Add your newly created repo as `origin`
  ```
  git remote add origin git@github.com:<your-github-username>/<your-github-username>.github.io.git
  ```

8. Push the changes
  ```
  git push -u origin master
  ```