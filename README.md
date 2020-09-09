### Hi there 👋, Welcome to my Poor Repo! Nothing you can find here.

```python
import logging

class ReadMe:

    def __init__(self, username="mragungsetiaji"):
        self.username = username
        self.name = 'A.S.'
        self.education = {
            'mathematic': ['Bachelor of Mathematic', 'YSU']
        }
        self.employment = {
            'data-department': ['Data Scientist', 'Data Engineer']
        }
        self.language: ["Python", "SQL", "Scala"],
        self.framework: {
            'API': ["flask", "fastAPI],
            'ML': ["scikit-learn", "tensorflow"],
        },
        databases: ["BigQuery"],
    },
    
    @classmethod
    def daily_activity() -> None:
        
        activities = [
            'Reading Medium',
            'Upgrading Data Framework',
            'Making notes with Bear',
            'Finding Vulnerability using ParrotOS',
            'Sleeping',
        ]
        
        while True:
            for activity in activities:
                logging.debug("I am {}".format(activity))
                
if __name__ == "__main__":
     me = ReadMe()
```


