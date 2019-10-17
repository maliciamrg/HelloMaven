# Hello Maven

GitHub Actions Maven Deploy Sample Repository

`settings.xml`

```xml
    <servers>
        <server>
            <id>github</id>
                <username>${env.GITHUB_USERNAME}</username> 
                <password>${env.GITHUB_PASSWORD}</password>
        </server>
    </servers>
```

Add the secrets for `GITHUB_USERNAME` and `GITHUB_PASSWORD` in the projects GitHUB Secret store:  
_Settings > Secrets > Add new secret_
