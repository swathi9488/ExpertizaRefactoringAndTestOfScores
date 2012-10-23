ExpertizaRefactoringAndTestOfScores
===================================

We have refactored the models/score.rb and models/score_cache.rb files. Unit test cases for these two files have been written

How to clone our repository and run it in your local machine?

1. Clone the following repository using the way:
https://github.com/swathi9488/ExpertizaRefactoringAndTestOfScores and open the RubyMine project in RubyMine

2. Make changes to database.yml:
the "password" field in "development" & "test" section to your mysql password

3. Run the following rake tasks:
db:create:all
db:migrate
db:test:load

4. Run the Development environment whether it successfully runs without any errors 

5. go to http://localhot:3000

6. go to the file test/unit/score_test.rb. Right click on the "class ScoreTest" line. Select option "Run ScoreTest".
   
7. go to the file test/unit/score_cache_test.rb. Right click on the "class ScoreCacheTest" line. Select option "Run ScoreCacheTest".
