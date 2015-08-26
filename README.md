# Code Retreat testing

You have a choice of (at least) three frameworks. This repo includes tests for:

1. [Test::Unit](https://github.com/test-unit/test-unit)
2. [minitest](https://github.com/seattlerb/minitest)
3. [RSpec](http://rspec.info)

Use whichever one you like the most!

To see whether you have the testing tools installed correctly, you can run the following commands:

```bash
ruby test_unit_test.rb # 1 tests, 1 assertions, 0 failures
ruby minitest_test.rb  # 1 runs, 1 assertions, 0 failures
rspec rspec_spec.rb    # 1 example, 0 failures
```

I've created a Gemfile that will install each of these tools, if you need. Install them with:

```bash
gem install bundler
bundle install
```

That's it!

## What about other frameworks?

You might be interested in using one of the following testing frameworks:

* [Cucumber](https://cucumber.io)
* [Spinach](https://github.com/codegram/spinach)
* [Approvals](https://github.com/kytrinyx/approvals)
* Something else??

Feel free! And why not help out your fellow code retreaters in the process? Here's how you can add a new framework to this project:

1. Create an example test file
2. Add any relevant gems to the Gemfile
3. Update this README.md
4. [Send a pull request!](https://help.github.com/articles/using-pull-requests/)
