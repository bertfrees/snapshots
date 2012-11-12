# [bertfrees.github.com/snapshots](http://bertfrees.github.com/snapshots)

## Usage

To use my snapshots, add this to your pom.xml:

    <repositories>
        <repository>
            <id>bertfrees-github-snapshots</id>
            <url>http://bertfrees.github.com/snapshots</url>
            <releases>
                <enabled>false</enabled>
            </releases>
            <snapshots>
                <enabled>true</enabled>
            </snapshots>
        </repository>
    </repositories>
