Debugging Workshop
==================

**As a first read**, a pill by Amazing Leo: https://github.com/makersacademy/course/blob/master/pills/debugging.md
  * debugging = playing Sherlock Holmes: follow the clues

1. Examples of failed tests
----------------------------
  * common error types:
      - syntax error is basically a syntax error
      - noMethodError
      - nilClass
      - singleton (when using doubles)

2. How to solve them
---------------------
1-2-3: 
  1. Have I pulled before editing?
  2. Have I saved my changes before running tests?
  3. Have I migrated my database?

  * be very methodical  
  * how to read a stack trace
  * use `p`
  * committing regularly (AFTER EACH GREEN TEST)
  * use `git diff`

3. Tools to use
---------------
* Ruby
  * pry and byebug
  * seeing is believing (Atom)
  * launchy for Capybara 
  * ruby-lint

* Javascript
  * Chrome Development Tools:
    * console output
    * breakpoints
  * JSHint (linter)




<!--* always `git pull` before making edits-->

<!--Debugging ideas-->

<!--* TDD, london v chicago-->
<!--* testing, expectations-->
<!--* stack traces-->
<!--* irb v pry, binding.pry-->
<!--* byebug-->
<!--* p v puts-->
<!--* p page.body-->
<!--* gem launchy save_and_open_page-->
<!--* debugging rails `debug`-->
<!--* http://guides.rubyonrails.org/debugging_rails_applications.html-->
<!--* https://github.com/dearshrewdwit/course/blob/master/pills/debugging.md-->
<!--* seeing is believing-->
