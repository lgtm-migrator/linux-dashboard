<h1 align="center">
    <a href="linuxdashboard.com"><img alt="Linux Dashboard" width="30%" src="https://github.com/chandlerlucius/linux-dashboard/blob/master/src/main/resources/com/utils/dashboard/img/logo-dark.svg"/></a>
</h1>

<p align="center">
    <strong>Simple Bash scripting project to generate linux server
    analytics with a Java Websocket wrapper</strong>
</p>

<p align="center">
    <a href="https://codecov.io/gh/chandlerlucius/linux-dashboard">
        <img 
        src="https://codecov.io/gh/chandlerlucius/linux-dashboard/branch/master/graph/badge.svg" 
        alt="Code Coverage" />
    </a>
    <a href="https://www.codacy.com/app/chandlerlucius/linux-dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=chandlerlucius/linux-dashboard&amp;utm_campaign=Badge_Grade">
        <img 
        src="https://api.codacy.com/project/badge/Grade/c25d8a8f98ee4993a15a6f23ecf88b37" 
        alt="Code Quality" />
    </a>
    <a href="https://sonarcloud.io/dashboard?id=com.utils%3Alinux-dashboard">
        <img 
        src="https://sonarcloud.io/api/project_badges/measure?project=com.utils%3Alinux-dashboard&metric=alert_status" 
        alt="Quality Gate" />
    </a>
    <a href="https://sonarcloud.io/dashboard?id=com.utils%3Alinux-dashboard">
        <img 
        src="https://sonarcloud.io/api/project_badges/measure?project=com.utils%3Alinux-dashboard&metric=sqale_rating" 
        alt="Maintainability Rating" />
    </a>
    <a href="https://sonarcloud.io/dashboard?id=com.utils%3Alinux-dashboard">
        <img 
        src="https://sonarcloud.io/api/project_badges/measure?project=com.utils%3Alinux-dashboard&metric=reliability_rating" 
        alt="Reliability Rating" />
    </a>
    <a href="https://sonarcloud.io/dashboard?id=com.utils%3Alinux-dashboard">
        <img 
        src="https://sonarcloud.io/api/project_badges/measure?project=com.utils%3Alinux-dashboard&metric=security_rating" 
        alt="Security Rating" />
    </a>
</p>

<p align="center">
    <a href="https://travis-ci.org/chandlerlucius/linux-dashboard">
        <img 
        src="https://travis-ci.org/chandlerlucius/linux-dashboard.svg" 
        alt="Build Status">
    </a>
    <a href="https://libraries.io/github/chandlerlucius/linux-dashboard">
        <img 
        src="https://img.shields.io/librariesio/github/chandlerlucius/linux-dashboard.svg" 
        alt="Dependency Status" />
    </a>
    <a href="https://github.com/chandlerlucius/linux-dashboard/releases/latest">
        <img 
        src="https://img.shields.io/github/tag-pre/chandlerlucius/linux-dashboard.svg"
         alt="Latest Release" />
    </a>
    <a href="https://github.com/chandlerlucius/linux-dashboard/releases">
        <img 
        src="https://img.shields.io/github/downloads/chandlerlucius/linux-dashboard/total.svg" 
        alt="Releases" />
    </a>
</p>

<p align="center">
    <a href="https://github.com/chandlerlucius/linux-dashboard/blob/master/LICENSE">
        <img 
        src="https://img.shields.io/github/license/chandlerlucius/linux-dashboard.svg" 
        alt="License" />
    </a>
    <a href="https://app.fossa.com/projects/git%2Bgithub.com%2Fchandlerlucius%2Flinux-dashboard?ref=badge_shield">
        <img 
        src="https://app.fossa.com/api/projects/git%2Bgithub.com%2Fchandlerlucius%2Flinux-dashboard.svg?type=shield" 
        alt="FOSSA Status" />
    </a>
    <a href="https://gitter.im/chandlerlucius/linux-dashboard">
        <img 
        src="https://badges.gitter.im/chandlerlucius/linux-dashboard.svg" 
        alt="Gitter Chat Room" />
    </a>
</p>

<p align="center">
    <a href="https://github.com/chandlerlucius/linux-dashboard/wiki">Wiki</a> | <a href="https://linuxdashboard.com">Live Demo</a>
</p>

# Intro

Linux Dashboard is bash script written to get basic server
analytic data and aggregate it into a json format.

It is encased in a Java wrapper using websockets
to provide the client machine with constantly updating data.

## Prerequisites

Java is needed to build/test/install/deploy the project.

## Installation / Deployment

### Installation

#### Download from source
1. Clone the repo
    ```bash
    git clone https://github.com/chandlerlucius/linux-dashboard
    ```
2. Navigate to repo directory
    ```bash
    cd linux-dashboard
    ```
3. Build project w/o tests
    ```bash
    ./mvnw clean install -DskipTests
    ```
4. Navigate to target directory
    ```bash
    cd target
    ```

#### Download manually

1. Download the jar
    ```bash
    wget https://github.com/chandlerlucius/linux-dashboard/releases/download/v1.0.0-alpha/linux-dashboard-1.0.0.jar
    ```

### Deployment

#### Deploy in foreground
```bash
java -jar linux-dashboard-1.0.0.jar
```

#### Deploy in background
```bash
nohup java -jar linux-dashboard-1.0.0.jar &
```

## Running the tests

### Use maven to run the tests
```bash
./mvnw test
```


## Support

For help, please use the [chat room](https://gitter.im/chandlerlucius/linux-dashboard).

## License

[MIT](LICENSE)

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fchandlerlucius%2Flinux-dashboard.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fchandlerlucius%2Flinux-dashboard?ref=badge_large)

## Acknowledgements

<table>
    <caption>Source Frameworks</caption>
    <thead>
        <tr>
            <th>Site</th>
            <th>Name</th>
            <th>Type</th>
            <th>Source</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="https://javaee.github.io/tutorial/websocket.html" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars2.githubusercontent.com/u/23086798?s=200&v=4" alt="Java EE" height="30px"/>
                </a>
            </td>
            <td>Java Websocket API</td>
            <td>Full-duplex Communication Channel</td>
            <td>
                <a href="https://github.com/eclipse-ee4j/websocket-api" target="_blank" rel="noopener noreferrer">https://github.com/eclipse-ee4j/websocket-api</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="http://undertow.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars3.githubusercontent.com/u/2001898?s=200&v=4" alt="Undertow" height="30px"/>
                </a>
            </td>
            <td>Undertow</td>
            <td>Embedded Web Server</td>
            <td>
                <a href="https://github.com/undertow-io/undertow" target="_blank" rel="noopener noreferrer">https://github.com/undertow-io/undertow</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://materializecss.com/" target="_blank" rel="noopener noreferrer">
                    <img src="https://materializecss.com/res/materialize.svg" alt="Materialize" height="30px"/>
                </a>
            </td>
            <td>Materialize</td>
            <td>Responsive Web Design</td>
            <td>
                <a href="https://github.com/Dogfalo/materialize" target="_blank" rel="noopener noreferrer">https://github.com/Dogfalo/materialize</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://maven.apache.org/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars1.githubusercontent.com/u/47359?s=200&v=4" alt="Maven" height="30px"/>
                </a>
            </td>
            <td>Maven</td>
            <td>Java Build Tool</td>
            <td>
                <a href="https://github.com/apache/maven" target="_blank" rel="noopener noreferrer">https://github.com/apache/maven</a>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <caption>Test Frameworks</caption>
    <thead>
        <tr>
            <th>Site</th>
            <th>Name</th>
            <th>Type</th>
            <th>Source</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="https://junit.org/junit5/" target="_blank" rel="noopener noreferrer">
                    <img src="https://junit.org/junit5/assets/img/junit5-logo.png" alt="JUnit 5" height="30px"/>
                </a>
            </td>
            <td>JUnit 5</td>
            <td>Java Testing</td>
            <td>
                <a href="https://github.com/junit-team/junit5" target="_blank" rel="noopener noreferrer">https://github.com/junit-team/junit5</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://jestjs.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://jestjs.io/img/favicon/favicon.ico" alt="Jest" height="30px"/>
                </a>
            </td>
            <td>Jest</td>
            <td>Javascript Testing</td>
            <td>
                <a href="https://github.com/facebook/jest" target="_blank" rel="noopener noreferrer">https://github.com/facebook/jest</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://github.com/bats-core" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars2.githubusercontent.com/u/32112113?s=200&v=4" alt="BATS" height="30px"/>
                </a>
            </td>
            <td>BATS</td>
            <td>Shell Testing</td>
            <td>
                <a href="https://github.com/bats-core/bats-core" target="_blank" rel="noopener noreferrer">https://github.com/bats-core/bats-core</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://nodejs.org/en/" target="_blank" rel="noopener noreferrer">
                    <img src="https://nodejs.org/static/images/logo.svg" alt="Node.js" height="30px"/>
                </a>
            </td>
            <td>Node.js</td>
            <td>Javascript Test Tool</td>
            <td>
                <a href="https://github.com/nodejs/node" target="_blank" rel="noopener noreferrer">https://github.com/nodejs/node</a>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <caption>Code Coverage</caption>
    <thead>
        <tr>
            <th>Site</th>
            <th>Name</th>
            <th>Language</th>
            <th>Source</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="https://www.eclemma.org/jacoco/" target="_blank" rel="noopener noreferrer">
                    <img src="https://www.eclemma.org/favicon.ico" alt="Jacoco" height="30px"/>
                </a>
            </td>
            <td>Jacoco</td>
            <td>java</td>
            <td>
                <a href="https://github.com/jacoco/jacoco" target="_blank" rel="noopener noreferrer">https://github.com/jacoco/jacoco</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://jestjs.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://jestjs.io/img/favicon/favicon.ico" alt="Jest" height="30px"/>
                </a>
            </td>
            <td>Jest</td>
            <td>javascript</td>
            <td>
                <a href="https://github.com/facebook/jest" target="_blank" rel="noopener noreferrer">https://github.com/facebook/jest</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://simonkagstrom.github.io/kcov/" target="_blank" rel="noopener noreferrer">kcov</a>
            </td>
            <td>kcov</td>
            <td>shell</td>
            <td>
                <a href="https://github.com/SimonKagstrom/kcov" target="_blank" rel="noopener noreferrer">https://github.com/SimonKagstrom/kcov</a>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <caption>Code Lifecycle Tools</caption>
    <thead>
        <tr>
            <th>Site</th>
            <th>Name</th>
            <th>Type</th>
            <th>Source</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="https://travis-ci.org/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars0.githubusercontent.com/u/639823?s=200&v=4" alt="Travis CI" height="30px"/>
                </a>
            </td>
            <td>Travis CI</td>
            <td>CI / CD</td>
            <td>
                <a href="https://github.com/travis-ci" target="_blank" rel="noopener noreferrer">https://github.com/travis-ci</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://codecov.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars0.githubusercontent.com/u/8226205?s=200&v=4" alt="Codecov" height="30px"/>
                </a>
            </td>
            <td>Codecov</td>
            <td>Code Coverage</td>
            <td>
                <a href="https://github.com/codecov" target="_blank" rel="noopener noreferrer">https://github.com/codecov</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://sonarcloud.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://sonarcloud.io/favicon.ico" alt="Sonarcloud" height="30px"/>
                </a>
            </td>
            <td>Sonarcloud</td>
            <td>Code Quality</td>
            <td>
                <a href="https://github.com/SonarSource" target="_blank" rel="noopener noreferrer">https://github.com/SonarSource</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://app.codacy.com/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars1.githubusercontent.com/u/1834093?s=200&v=4" alt="Codacy" height="30px"/>
                </a>
            </td>
            <td>Codacy</td>
            <td>Code Quality</td>
            <td>
                <a href="https://github.com/codacy" target="_blank" rel="noopener noreferrer">https://github.com/codacy</a>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <caption>Github Integrations</caption>
    <thead>
        <tr>
            <th>Site</th>
            <th>Name</th>
            <th>Type</th>
            <th>Source</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="https://fossa.com/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars0.githubusercontent.com/u/9543448?s=200&v=4" alt="FOSSA" height="30px"/>
                </a>
            </td>
            <td>FOSSA</td>
            <td>License Checker</td>
            <td>
                <a href="https://github.com/fossas" target="_blank" rel="noopener noreferrer">https://github.com/fossas</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://libraries.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars1.githubusercontent.com/u/11243589?s=200&v=4" alt="Libraries.io" height="30px"/>
                </a>
            </td>
            <td>Libraries.io</td>
            <td>Dependency Scanner</td>
            <td>
                <a href="https://github.com/librariesio/libraries.io" target="_blank" rel="noopener noreferrer">https://github.com/librariesio/libraries.io</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://www.gitguardian.com/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars3.githubusercontent.com/u/27360172?s=200&v=4" alt="GitGuardian" height="30px"/>
                </a>
            </td>
            <td>GitGuardian</td>
            <td>Credential Leak Detector</td>
            <td>
                <a href="https://github.com/GitGuardian" target="_blank" rel="noopener noreferrer">https://github.com/GitGuardian</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://bolt.whitesourcesoftware.com/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars2.githubusercontent.com/u/1539627?s=200&v=4" alt="Whitesource Bolt" height="30px"/>
                </a>
            </td>
            <td>Whitesource Bolt</td>
            <td>Vunerability Finder</td>
            <td>
                <a href="https://github.com/whitesource" target="_blank" rel="noopener noreferrer">https://github.com/whitesource</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://gitter.im/" target="_blank" rel="noopener noreferrer">
                    <img src="https://avatars2.githubusercontent.com/u/5990364?s=200&v=4" alt="Gitter" height="30px"/>
                </a>
            </td>
            <td>Gitter</td>
            <td>Support Chat Room</td>
            <td>
                <a href="https://github.com/gitterHQ" target="_blank" rel="noopener noreferrer">https://github.com/gitterHQ</a>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <caption>Linting Tools</caption>
    <thead>
        <tr>
            <th>Site</th>
            <th>Name</th>
            <th>Language</th>
            <th>Source</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="https://pmd.github.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://pmd.github.io/img/pmd_logo.png" alt="PMD" height="30px"/>
                </a>
            </td>
            <td>PMD</td>
            <td>java</td>
            <td>
                <a href="https://github.com/pmd/pmd" target="_blank" rel="noopener noreferrer">https://github.com/pmd/pmd</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://spotbugs.github.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://spotbugs.github.io/images/logos/spotbugs_icon_only_zoom_256px.png" alt="Spotbugs" height="30px"/>
                </a>
            </td>
            <td>Spotbugs</td>
            <td>java</td>
            <td>
                <a href="https://github.com/spotbugs/spotbugs" target="_blank" rel="noopener noreferrer">https://github.com/spotbugs/spotbugs</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="http://checkstyle.sourceforge.net/" target="_blank" rel="noopener noreferrer">
                    <img src="http://checkstyle.sourceforge.net/images/header-checkstyle-logo.png" alt="Checkstyle" height="30px"/>
                </a>
            </td>
            <td>Checkstyle</td>
            <td>java</td>
            <td>
                <a href="https://github.com/checkstyle/checkstyle" target="_blank" rel="noopener noreferrer">https://github.com/checkstyle/checkstyle</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://jshint.com/" target="_blank" rel="noopener noreferrer">
                    <img src="https://jshint.com/res/jshint-dark.png" alt="JSHint" height="30px"/>
                </a>
            </td>
            <td>JSHint</td>
            <td>javascript</td>
            <td>
                <a href="https://github.com/jshint/jshint" target="_blank" rel="noopener noreferrer">https://github.com/jshint/jshint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://eslint.org/" target="_blank" rel="noopener noreferrer">
                    <img src="https://eslint.org/img/logo.svg" alt="ESLint" height="30px"/>
                </a>
            </td>
            <td>ESLint</td>
            <td>javascript</td>
            <td>
                <a href="https://github.com/eslint/eslint" target="_blank" rel="noopener noreferrer">https://github.com/eslint/eslint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="http://csslint.net/" target="_blank" rel="noopener noreferrer">
                    <img src="http://csslint.net/favicon.ico" alt="CSSLint" height="30px"/>
                </a>
            </td>
            <td>CSSLint</td>
            <td>css</td>
            <td>
                <a href="https://github.com/CSSLint/csslint" target="_blank" rel="noopener noreferrer">https://github.com/CSSLint/csslint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://stylelint.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://stylelint.io/_/src/components/DefaultHeadMeta/favicon.7f672624abe02127db4972965ea73002.ico" alt="Stylelint" height="30px"/>
                </a>
            </td>
            <td>Stylelint</td>
            <td>css</td>
            <td>
                <a href="https://github.com/stylelint/stylelint" target="_blank" rel="noopener noreferrer">https://github.com/stylelint/stylelint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://dlaa.me/markdownlint/" target="_blank" rel="noopener noreferrer">
                    <img src="https://dlaa.me/markdownlint.png?crc32=2a731dd4" alt="Markdownlint" height="30px"/>
                </a>
            </td>
            <td>MarkdownLint</td>
            <td>markdown</td>
            <td>
                <a href="https://github.com/DavidAnson/markdownlint" target="_blank" rel="noopener noreferrer">https://github.com/DavidAnson/markdownlint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://remark.js.org/" target="_blank" rel="noopener noreferrer">
                    <img src="https://raw.githubusercontent.com/remarkjs/remark-lint/02295bc/logo.svg?sanitize=true" alt="Remark-Lint" height="30px"/>
                </a>
            </td>
            <td>Remark-Lint</td>
            <td>markdown</td>
            <td>
                <a href="https://github.com/remarkjs/remark-lint" target="_blank" rel="noopener noreferrer">https://github.com/remarkjs/remark-lint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://www.shellcheck.net/" target="_blank" rel="noopener noreferrer">
                    <img src="https://www.shellcheck.net/favicon.ico" alt="Shellcheck" height="30px"/>
                </a>
            </td>
            <td>Shellcheck</td>
            <td>shell</td>
            <td>
                <a href="https://github.com/koalaman/shellcheck" target="_blank" rel="noopener noreferrer">https://github.com/koalaman/shellcheck</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://htmlhint.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://htmlhint.io/favicon.ico" alt="HTMLHint" height="30px"/>
                </a>
            </td>
            <td>HTMLHint</td>
            <td>html</td>
            <td>
                <a href="https://github.com/htmlhint/HTMLHint" target="_blank" rel="noopener noreferrer">https://github.com/htmlhint/HTMLHint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="https://jsonlint.com/" target="_blank" rel="noopener noreferrer">
                    <img src="https://jsonlint.com/favicon.ico" alt="JSONLint" height="30px"/>
                </a>
            </td>
            <td>JSONLint</td>
            <td>json</td>
            <td>
                <a href="https://github.com/zaach/jsonlint" target="_blank" rel="noopener noreferrer">https://github.com/zaach/jsonlint</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="http://yamllint.com/" target="_blank" rel="noopener noreferrer">YAMLLint</a>
            </td>
            <td>YAMLLint</td>
            <td>yaml</td>
            <td>
                <a href="https://github.com/adrienverge/yamllint" target="_blank" rel="noopener noreferrer">https://github.com/adrienverge/yamllint</a>
            </td>
        </tr>
    </tbody>
</table>
