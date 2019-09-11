# spamlord

  
## Spamlord 
On the web, many people who want to give their email addresses or phone numbers for people to contact them will try to make it hard for spammers to automatically search text for email addresses and phone numbers by giving non-standard forms of them, sometimes called obfuscation. You may have seen examples like: jurafsky(at)cs.stanford.edu jurafsky at csli dot stanford dot edu

In the spamlord.py there are regular expressions that help identify these obscured emails and phone numbers.

## Running this project
Step 1. Clone this repo. 
Step 2. Use a regex editor to test patterns, then add them to the starter code in SpamLord.py https://regex101.com (make sure you select Flavor > Python) 

On terminal on MacOS or Command prompt on windows and run the python file.

```
python SpamLord.py data/dev data/devGOLD
```

Try to gradually improve your accuracy by adding additional match patterns to Spamlord.py.
