
 TeamCity plugin

 ## create maven plugin project
```shell
mvn archetype:generate -DarchetypeGroupId=org.jetbrains.teamcity.archetypes -DarchetypeArtifactId=teamcity-plugin -DarchetypeVersion=RELEASE -DgroupId=com.zerothreatai -DartifactId=zt-teamcity-plugin -Dversion=1.0-SNAPSHOT -Dpackage=com.zerothreatai.teamcity -DinteractiveMode=false -DteamcityVersion=2024.12 
```

## build plugin
`mvn clean package`

user root/target/<your-plugin-name>.zip
