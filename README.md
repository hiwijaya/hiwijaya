``` python
class HappyIndraWijaya:

    def __init__(self):
        self.username = 'hiwijaya'
        self.name = 'Happy Indra Wijaya'
        self.email = 'me@hiwijaya.com'
        self.web = 'https://hiwijaya.com'
        self.code = {
            'frontend': ['ReactJS', 'React Native', 'AngularJS', 'Android', 'Tailwind', 'Gatsby', 'Wordpress'],
            'backend': ['Java', 'Python', 'Spring', 'Flask', 'SQLAlchemy'],
            'database': ['PostgreSQL', 'MySQL', 'MongoDB', 'Elasticsearch', 'Realm', 'SQLite'],
            'devops': ['Docker', 'Kubernetes', 'Nginx', 'Jenkins', 'AWS', 'Digital Ocean', 'Netlify'],
            'misc': ['Firebase', 'Redis', 'Kibana', 'Logstash', 'Kafka', 'Prometheus']
        }

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = HappyIndraWijaya()

```
