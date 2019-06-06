# Blogger Foo

Repo of _Blogger Foo_ personal website.

# How to get your own blogging website

1. Clone it
  ```
  git clone https://github.com/bloggerfoo/bloggerfoo.github.io myblog
  ```

2. Enter into the directory
  ```
  cd myblog
  ```

3. Replace content of following pages as per your need:
    1. `_config.yml`
    2. `_data/about.yml`
    3. `_data/home.yml`
    4. `_data/projects.yml`
    5. `_posts`: Delete existing and write your own post in 
       [Jekyll format](https://jekyllrb.com/docs/step-by-step/08-blogging/)

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

9. Visit your blogging website at `https://<your-github-username>.github.io`.
10. Enjoyee! :blush:

# Contribution Guidelines

1. Fork the project.
2. Clone the project at your local machine.
3. Create a separate branch with short & sweet name of `What feature or fix you are doing`.
4. Commit the changes.
5. Git push to your forked repo.
6. Send a pull request.
