# Yeoman generator for DevOps Dashboard widgets

> Yeoman generator for [devops-dashboard](https://crig.koroscil@stash.secure.root9b.com/dev/devops-dashboard) widgets.

## Dependencies

You must have the following installed to use this generator

* [npm](https://www.npmjs.com/)
* [yeoman](http://yeoman.io/)


## Usage

* Install `generator-devops-dashboard-widget`:

```bash
npm install -g git+https://crig.koroscil@stash.secure.root9b.com/dev/generator-devops-dashboard-widget.git
```

* Make a new directory, and `cd` into it:

```
mkdir devops-dashboard-widget-[your project name] && cd $_
```

* Run `yo devops-dashboard-widget`:

```
yo devops-dashboard-widget
```

![yo devops-dashboard-widget](screenshots/yo.png)


* Run `gulp` for building and `gulp serve` for preview


## Deploy your widget

After you are done developing your widget, commit your code to the DevOps Dashboard

1. Create a [feature Branch](https://www.atlassian.com/git/tutorials/comparing-workflows#feature-branch-workflow) on the [DevOps Dashboard](https://stash.secure.root9b.com/projects/DEV/repos/devops-dashboard/browse)
2. Add your widget (release files only) to the DevOps Dashboard:

    <pre>
    devops-dashboard
    ├── package.json
    └── src
        ├── app
        │   ├── app.js
        │   └── widgets
        │       ├── <b>mywidget</b>
        │       │   ├── <b>edit.html</b>
        │       │   ├── <b>mywidget.module.js</b>
        │       │   └── <b>view.html</b>
        │       └── widgets.module.js
        ├── index.html
        └── login.html
    </pre>

3. Commit your code
4. Submit a pull request


## License

The MIT License

Copyright (c) 2015, Sebastian Sdorra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
