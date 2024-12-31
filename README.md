# pinceladasmarina 
#### SO: Fedora 40
#### Theme: roxo-jekyll 
#### Repo: https://github.com/StaticMania/roxo-jekyll.git

## Steps to Set Up the Project

### Prerequisites

Make sure you have the following installed on your local machine:

- Ruby
- Bundler
- Jekyll

### 1. Clone the repository of the theme:

```bash
git clone https://github.com/StaticMania/roxo-jekyll
```

### 2. Install dependencies

Navigate to the project directory:

```bash
cd roxo-jekyll
```

Then, install the dependencies using the `bundle install` command:

```bash
bundle install
```
>**Note:** Check the installed versions and adjust the `Gemfile` and `Gemfile.lock` to resolve any issues with gem versions.

### 3. Serve Locally

To serve the site locally, use the following command:

```bash
bundler exec jekyll serve
```

> **Note:** In my case, I had to manually install some gems that weren't being installed with the current versions when running `bundle install` due to version conflicts. For example, the `rexml` gem required by `kramdown` and the `webrick` gem. Afterward, I added the `webrick` gem to the `Gemfile` and ran `bundle install` again, which increased the number of installed gems. From there, I executed `bundler exec jekyll serve` and everything worked as expected.

### 4. Build Your Site

Once everything is set up, build the site using the following command:

```bash
jekyll build
```

This will generate the static files in the `_site` directory.

---

That's it! You should now have your site running locally. If you encounter any issues with gems or dependencies, make sure to check the `Gemfile` and `Gemfile.lock` for version compatibility.




