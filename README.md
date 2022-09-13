### React 기반 Gatsby로 기술 블로그 개발하기 
###### https://macaronics.net/index.php/m04/react/view/1922

<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->


<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's 기본 시작
</h1>

이 기본 상용구로 프로젝트를 시작하세요. 이 스타터는 React용 엄청나게 빠른 앱 생성기를 사용하여 빠르게 시작하고 실행하는 데 필요할 수 있는 기본 Gatsby 구성 파일과 함께 제공됩니다.

더 구체적인 아이디어가 있습니까? [공식 및 커뮤니티 생성 스타터](https://www.gatsbyjs.com/docs/gatsby-starters/)의 활기찬 컬렉션을 확인하고 싶을 수도 있습니다._

## 🚀 Quick start

1.  **개츠비 사이트 만들기.**

   
    Gatsby CLI([설치 지침](https://www.gatsbyjs.com/docs/tutorial/part-0/#gatsby-cli))를 사용하여 기본 스타터를 지정하여 새 사이트를 만듭니다.

    ```shell
    # create a new Gatsby site using the default starter
    gatsby new my-default-starter https://github.com/gatsbyjs/gatsby-starter-default
    ```

1.  **개발 시작.**

   새 사이트의 디렉토리로 이동하여 시작하십시오.

    ```shell
    cd my-default-starter/
    gatsby develop
    ```

1.  **소스 코드를 열고 편집 시작!**

    다음에서 실행 중  :  `http://localhost:8000`!

    _참고: 두 번째 링크인 _`http://localhost:8000/___graphql`_도 표시됩니다. 이것은 데이터 쿼리를 실험하는 데 사용할 수 있는 도구입니다. [Gatsby Tutorial](https://www.gatsbyjs.com/docs/tutorial/part-4/#use-graphiql-to-explore-the-data-layer-and-write-)에서 이 도구를 사용하는 방법에 대해 자세히 알아보세요. graphql 쿼리)._

   선택한 코드 편집기에서 `my-default-starter` 디렉토리를 열고 `src/pages/index.js`를 편집합니다. 변경 사항을 저장하면 브라우저가 실시간으로 업데이트됩니다!

## 🚀 빠른 시작 (Gatsby Cloud)

[Gatsby Cloud](https://www.gatsbyjs.com/cloud/)에서 한 번의 클릭으로 이 스타터를 배포합니다.

[<img src="https://www.gatsbyjs.com/deploynow.svg" alt="Deploy to Gatsby Cloud">](https://www.gatsbyjs.com/dashboard/deploynow?url=https://github.com/gatsbyjs/gatsby-starter-default)

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/node_modules`**: 이 디렉토리에는 프로젝트가 의존하는 모든 코드 모듈(npm 패키지)이 자동으로 설치됩니다.

2.  **`/src`**: 이 디렉토리에는 사이트 헤더 또는 페이지 템플릿과 같이 사이트 프론트 엔드에 표시되는 내용(브라우저에 표시되는 내용)과 관련된 모든 코드가 포함됩니다. `src`는 "소스 코드"에 대한 규칙입니다.

3.  **`.gitignore`**: 이 파일은 버전 기록을 추적하거나 유지하지 않아야 하는 파일을 git에 알려줍니다.

4.  **`.prettierrc`**: [Prettier](https://prettier.io/) 설정 파일입니다. Prettier는 코드 형식을 일관되게 유지하는 데 도움이 되는 도구입니다.

5.  **`gatsby-browser.js`**: 이 파일은 Gatsby가 [Gatsby 브라우저 API](https://www.gatsbyjs.com/docs/reference/config-files/gatsby-browser/)(있는 경우)의 사용을 찾을 것으로 예상하는 위치입니다. 이를 통해 브라우저에 영향을 미치는 기본 Gatsby 설정을 사용자 정의/확장할 수 있습니다.

6.  **`gatsby-config.js`**: Gatsby 사이트의 기본 설정 파일입니다. 여기에서 사이트 제목 및 설명, 포함하려는 Gatsby 플러그인 등과 같은 사이트(메타데이터)에 대한 정보를 지정할 수 있습니다. ([config docs](https://www.gatsbyjs.com 참조) /docs/reference/config-files/gatsby-config/) 참조).

7.  **`gatsby-node.js`**: 이 파일은 Gatsby가 [Gatsby Node API](https://www.gatsbyjs.com/docs/reference/config-files/gatsby-node/)(있는 경우)의 사용을 찾을 것으로 예상하는 위치입니다. 이를 통해 사이트 빌드 프로세스의 일부에 영향을 미치는 기본 Gatsby 설정을 사용자 정의/확장할 수 있습니다.

8.  **`gatsby-ssr.js`**: 이 파일은 Gatsby가 [Gatsby 서버 측 렌더링 API](https://www.gatsbyjs.com/docs/reference/config-files/gatsby-ssr/)(있는 경우)의 사용을 찾을 것으로 예상하는 위치입니다. 이를 통해 서버 측 렌더링에 영향을 미치는 기본 Gatsby 설정을 사용자 지정할 수 있습니다.

9.  **`LICENSE`**: 이 Gatsby 스타터는 0BSD 라이선스에 따라 라이선스가 부여됩니다. 즉, 이 파일을 자리 표시자로 보고 자신의 라이선스로 바꿀 수 있습니다.

10. **`package-lock.json`** (먼저 아래 `package.json`을 참조하십시오). 이것은 프로젝트에 설치된 npm 종속성의 정확한 버전을 기반으로 자동 생성된 파일입니다. **(이 파일을 직접 변경하지 않습니다).**

11. **`package.json`**: 메타데이터(프로젝트 이름, 작성자 등)와 같은 항목이 포함된 Node.js 프로젝트의 매니페스트 파일입니다. 이 매니페스트는 npm이 프로젝트에 설치할 패키지를 아는 방법입니다.

12. **`README.md`**: 프로젝트에 대한 유용한 참조 정보가 포함된 텍스트 파일입니다.

## 🎓 Learning Gatsby

더 많은 지침을 찾고 계십니까? Gatsby의 전체 문서는 [웹사이트](https://www.gatsbyjs.com/)에 있습니다. 다음은 시작할 수 있는 몇 가지 장소입니다.

- **대부분의 개발자는 다음으로 시작하는 것이 좋습니다. [Gatsby로 사이트를 만들기 위한 심층 튜토리얼](https://www.gatsbyjs.com/tutorial/).** 당신의 능력 수준에 대해 전혀 가정하지 않고 시작하여 프로세스의 모든 단계를 안내합니다.

- **코드 샘플로 바로 들어가려면 [to our documentation](https://www.gatsbyjs.com/docs/).** 특히 사이드바에서 _Guides_, _API Reference_ 및 _Advanced Tutorials_ 섹션을 확인하세요.

## 💫 배포

[Gatsby를 위해 구축된 유일한 클라우드에서 구축, 배포 및 호스팅](https://www.gatsbyjs.com/products/cloud/)

Gatsby Cloud는 최신 개발자 경험과 최적화된 글로벌 에지 네트워크를 결합하는 Gatsby 프레임워크용으로 특별히 구축된 엔드 투 엔드 클라우드 플랫폼입니다.

<!-- AUTO-GENERATED-CONTENT:END -->
