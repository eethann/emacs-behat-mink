# Emacs Behat Mink Tools

This repository contains snippets to make authoring Behat tests for a web application more efficient.  This includes the default `giv`,`whe`,`the`,`and`, etc. templates that come with the [cucumber.el](https://github.com/michaelklishin/cucumber.el) feature-mode.  In addition to those, the following conventions are used:

   * `g_key` is used for "Given" steps, currently just `g_on` for `Given I am on "page"`.
   * `w_key` is used for "When" steps, such as `w_go` for `When I go to "page"` or `w_follow` for `When I follow "link"`.
   * `t_key` is used for "Then" steps, such as `t_code` for `Then the response code should be {code}`.
   * `t_-key` is used for negative statements, such as `t_-code` for `Then the response code should not be {code}`.
   
This has not been extensively tested aside from my personal system.  If you find issues with it please contribute issue reports and pull requests!