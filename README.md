Slurp sales info from tradme website
Runs hourly with cron on the small laptop

cron entry
*/14 * * * * /home/danie/Development/trademe_mining/mine.sh

mine.sh
/home/danie/Downloads/jdk1.8.0_66/bin/java -jar /home/danie/Development/trademe_mining/trademe-0.0.3-SNAPSHOT-jar-with-dependencies.jar /home/danie/Development/trademe_mining/ ll
