Insight Data Engineering - Coding Challenge
===========================================================

This implementation is done in Python 2.7.6. Following updated modules/packages are necessary for this implementation to run:
import simplejson, pandas, datetime

InsightChallenge/insight_testsuite/run_tests.sh referring the python file InsightChallenge/src/Average_degree.py to calculate the average degrees. 

#Algorithm Steps:
1. Open the tweets.txt file under tweet_input folder 
2. For reach record in the tweet input file parse the record to json format, ignore if it has limit time stamp and pass to next record. 
3. Get the created_at timestamp and list of hash tags 
4. Update Average score, hash tags and timestamp within the window pertaining to the given conditions and write to the output.txt file
5. Close the files and exit

After the program is executed, there will be a output.txt file with average degree under the tweet_output folder
