This project extends the JDT.LS by providing an extension point for `org.eclipse.jdt.ls.core.delegateCommandHandler`. See `SampleDelegateCommandHandler`. 

This project is built using [Eclipse Tycho](https://www.eclipse.org/tycho/) and requires at least [maven 3.0](http://maven.apache.org/download.html) to be built via CLI. 
Simply run :

    mvn install

The first run will take quite a while since maven will download all the required dependencies in order to build everything.

In order to use the generated eclipse plugins in Eclipse, you will need [m2e] (https://www.eclipse.org/m2e) 
and the [m2eclipse-tycho plugin](https://github.com/tesla/m2eclipse-tycho/). Update sites to install these plugins : 

* m2e stable update site : http://download.eclipse.org/technology/m2e/releases/
* m2eclipse-tycho dev update site : http://repo1.maven.org/maven2/.m2e/connectors/m2eclipse-tycho/0.8.1/N/LATEST/

## Code of Conduct
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkonveyor%2Fjava-analyzer-bundle.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkonveyor%2Fjava-analyzer-bundle?ref=badge_shield)

Refer to our [Code of Conduct page](https://github.com/konveyor/community/blob/main/CODE_OF_CONDUCT.md) for detailed information 


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkonveyor%2Fjava-analyzer-bundle.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkonveyor%2Fjava-analyzer-bundle?ref=badge_large)