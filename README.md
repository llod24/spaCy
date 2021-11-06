<a href="https://explosion.ai"><img src="https://explosion.ai/assets/img/logo.svg" width="125" height="125" align="right" /></a>

# spaCy: 산업용 자연어처리

spaCy는 Python 및 Cython의 **향상된 자연어 처리**를 위한 라이브러리입니다.
최신 연구를 기반으로 구축되었으며 처음부터 실제 제품에 사용되도록 설계되었습니다.

spaCy는 [사전에 학습된 파이프라인](https://spacy.io/models)과 함께 제공되며 현재 **60개 이상의 언어**에
대한 토큰화 및 훈련을 지원합니다. 태그 지정, 구문 분석, **명명된 엔티티 인식**, **텍스트 분류**와 BERT와 같은 사전 훈련된 **변압기**를 통한 멀티태스킹 학습뿐만 아니라 
생산 준비가 된 [**사전에 학습된 시스템**](https://spacy.io/usage/training)과 쉬운 모델 패키지, 배포 및 워크 플로우 관리를 위한 최첨단 속도와 **신경망 모델**이 특징입니다. 
spaCy는 MIT 라이선스에 따라 출시된 상용 오픈 소스 소프트웨어입니다.

💫 **3.0 버젼 출시!**
[여기서 릴리스 노트를 확인하세요](https://github.com/explosion/spaCy/releases)

[![Azure 파이프라인](https://img.shields.io/azure-devops/build/explosion-ai/public/8/master.svg?logo=azure-pipelines&style=flat-square&label=build)](https://dev.azure.com/explosion-ai/public/_build?definitionId=8)
[![최근 배포 버젼](https://img.shields.io/github/release/explosion/spacy.svg?style=flat-square&logo=github)](https://github.com/explosion/spaCy/releases)
[![pypi 버젼](https://img.shields.io/pypi/v/spacy.svg?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/spacy/)
[![conda 버젼](https://img.shields.io/conda/vn/conda-forge/spacy.svg?style=flat-square&logo=conda-forge&logoColor=white)](https://anaconda.org/conda-forge/spacy)
[![Python wheels](https://img.shields.io/badge/wheels-%E2%9C%93-4c1.svg?longCache=true&style=flat-square&logo=python&logoColor=white)](https://github.com/explosion/wheelwright/releases)
[![코드 스타일: black](https://img.shields.io/badge/code%20style-black-000000.svg?style=flat-square)](https://github.com/ambv/black)
<br />
[![PyPi 다운로드](https://static.pepy.tech/personalized-badge/spacy?period=total&units=international_system&left_color=grey&right_color=orange&left_text=pip%20downloads)](https://pypi.org/project/spacy/)
[![Conda 다운로드](https://img.shields.io/conda/dn/conda-forge/spacy?label=conda%20downloads)](https://anaconda.org/conda-forge/spacy)
[![spaCy 트위터](https://img.shields.io/twitter/follow/spacy_io.svg?style=social&label=Follow)](https://twitter.com/spacy_io)

## 📖 문서

| 문서              |                                                                |
| -------------------------- | -------------------------------------------------------------- |
| ⭐️ **[spaCy 101]**        | spaCy가 처음이신가요? 여기 알아야 할 모든게 있습니다!              |
| 📚 **[사용법 가이드]**      | spaCy 사용법과 특징.                             |
| 🚀 **[새로워진 3.0 버젼]**       | 새로운 기능, 이전 버젼과의 비호환성 및 이송 가이드. |
| 🪐 **[프로젝트 템플릿]** | 복사, 수정 및 실행할 수 있는 엔드 투 엔드 워크 플로우.            |
| 🎛 **[API 참조]**      | spaCy's API에 대한 자세한 참조.                        |
| 📦 **[모델]**            | spaCy용으로 훈련된 파이프라인 다운로드.                          |
| 🌌 **[Universe]**          | spaCy 에코시스템의 플러그인, 확장, 데모 및 책. |
| 👩‍🏫 **[온라인 강좌]**     | 무료 대화형 온라인 강좌에서 spaCy를 배우세요.        |
| 📺 **[비디오]**            | 비디오 자습서, 대화 등이 포함된 YouTube 채널.      |
| 🛠 **[변경 기록]**          | 변경 사항 및 버전 기록.                                   |
| 💝 **[기여]**        | spaCy 프로젝트와 코드 베이스에 기여하는 방법.          |

[spacy 101]: https://spacy.io/usage/spacy-101
[new in v3.0]: https://spacy.io/usage/v3
[사용법 가이드]: https://spacy.io/usage/
[api 참조]: https://spacy.io/api/
[모델]: https://spacy.io/models
[universe]: https://spacy.io/universe
[videos]: https://www.youtube.com/c/ExplosionAI
[온라인 강좌]: https://course.spacy.io
[프로젝트 템플릿]: https://github.com/explosion/projects
[변경 기록]: https://spacy.io/usage#changelog
[기여]: https://github.com/explosion/spaCy/blob/master/CONTRIBUTING.md

## 💬 문의할 곳

spaCy 프로젝트는 **[@honnibal](https://github.com/honnibal)**,
**[@ines](https://github.com/ines)**, **[@svlandeg](https://github.com/svlandeg)**,
**[@adrianeboyd](https://github.com/adrianeboyd)** and **[@polm](https://github.com/polm)**에 의해 유지됩니다.
이메일을 통한 개별 지원은 제공할 수 없다는 점을 양해바랍니다.
우리는 또한 더 많은 사람들이 도움을 받을 수 있도록 공개적으로 도움을 공유하는 것이 훨씬 더 가치 있다고 믿습니다.

| Type                            | Platforms                               |
| ------------------------------- | --------------------------------------- |
| 🚨 **버그 제보**              | [GitHub Issue Tracker]                  |
| 🎁 **기능 요청 & 아이디어** | [GitHub Discussions]                    |
| 👩‍💻 **사용법 질문**          | [GitHub Discussions] · [Stack Overflow] |
| 🗯 **일반적인 논의**        | [GitHub Discussions]                    |

[github issue tracker]: https://github.com/explosion/spaCy/issues
[github discussions]: https://github.com/explosion/spaCy/discussions
[stack overflow]: https://stackoverflow.com/questions/tagged/spacy

## 특징

- **60개 이상의 언어**를 지원.
- 다른 언어와 작업을 위해 **학습된 파이프라인** 
- BERT와 같은 사전 훈련된 **변압기**
- 사전 훈련된 **단어 벡터** 및 임베딩 지원
- 최첨단 속도
- 생산 준비가 된 **사전에 학습된 시스템**
- 언어 기반 **토큰화**
- 명명된 **엔티티 인식**, 품사 태깅, 종속성 구문 분석, 문장 분할, **텍스트 분류**, 표제어, 형태학적 분석, 엔티티 연결 등을 위한 구성 요소
- **사용자 정의 구성 요소** 및 속성으로 쉽게 확장 가능
- **PyTorch**, **TensorFlow**와 다른 프레임워크의 사용자 정의 모델 지원
- 구문 및 NER을 위한 **비주얼라이저** 내장
- 쉬운 **모델 패키징**, 배포 및 워크플로 관리
- 견고하고 엄격하게 평가된 정확도

📖 **자세한 사항은 여기를 참고하세요
[사실, 수치 및 벤치마크](https://spacy.io/usage/facts-figures).**

## ⏳ Install spaCy

For detailed installation instructions, see the
[documentation](https://spacy.io/usage).

- **Operating system**: macOS / OS X · Linux · Windows (Cygwin, MinGW, Visual
  Studio)
- **Python version**: Python 3.6+ (only 64 bit)
- **Package managers**: [pip] · [conda] (via `conda-forge`)

[pip]: https://pypi.org/project/spacy/
[conda]: https://anaconda.org/conda-forge/spacy

### pip

Using pip, spaCy releases are available as source packages and binary wheels.
Before you install spaCy and its dependencies, make sure that
your `pip`, `setuptools` and `wheel` are up to date.

```bash
pip install -U pip setuptools wheel
pip install spacy
```

To install additional data tables for lemmatization and normalization you can
run `pip install spacy[lookups]` or install
[`spacy-lookups-data`](https://github.com/explosion/spacy-lookups-data)
separately. The lookups package is needed to create blank models with
lemmatization data, and to lemmatize in languages that don't yet come with
pretrained models and aren't powered by third-party libraries.

When using pip it is generally recommended to install packages in a virtual
environment to avoid modifying system state:

```bash
python -m venv .env
source .env/bin/activate
pip install -U pip setuptools wheel
pip install spacy
```

### conda

You can also install spaCy from `conda` via the `conda-forge` channel. For the
feedstock including the build recipe and configuration, check out
[this repository](https://github.com/conda-forge/spacy-feedstock).

```bash
conda install -c conda-forge spacy
```

### Updating spaCy

Some updates to spaCy may require downloading new statistical models. If you're
running spaCy v2.0 or higher, you can use the `validate` command to check if
your installed models are compatible and if not, print details on how to update
them:

```bash
pip install -U spacy
python -m spacy validate
```

If you've trained your own models, keep in mind that your training and runtime
inputs must match. After updating spaCy, we recommend **retraining your models**
with the new version.

📖 **For details on upgrading from spaCy 2.x to spaCy 3.x, see the
[migration guide](https://spacy.io/usage/v3#migrating).**

## 📦 Download model packages

Trained pipelines for spaCy can be installed as **Python packages**. This
means that they're a component of your application, just like any other module.
Models can be installed using spaCy's [`download`](https://spacy.io/api/cli#download)
command, or manually by pointing pip to a path or URL.

| Documentation              |                                                                  |
| -------------------------- | ---------------------------------------------------------------- |
| **[Available Pipelines]**  | Detailed pipeline descriptions, accuracy figures and benchmarks. |
| **[Models Documentation]** | Detailed usage and installation instructions.                    |
| **[Training]**             | How to train your own pipelines on your data.                    |

[available pipelines]: https://spacy.io/models
[models documentation]: https://spacy.io/usage/models
[training]: https://spacy.io/usage/training

```bash
# Download best-matching version of specific model for your spaCy installation
python -m spacy download en_core_web_sm

# pip install .tar.gz archive or .whl from path or URL
pip install /Users/you/en_core_web_sm-3.0.0.tar.gz
pip install /Users/you/en_core_web_sm-3.0.0-py3-none-any.whl
pip install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.0.0/en_core_web_sm-3.0.0.tar.gz
```

### Loading and using models

To load a model, use [`spacy.load()`](https://spacy.io/api/top-level#spacy.load)
with the model name or a path to the model data directory.

```python
import spacy
nlp = spacy.load("en_core_web_sm")
doc = nlp("This is a sentence.")
```

You can also `import` a model directly via its full name and then call its
`load()` method with no arguments.

```python
import spacy
import en_core_web_sm

nlp = en_core_web_sm.load()
doc = nlp("This is a sentence.")
```

📖 **For more info and examples, check out the
[models documentation](https://spacy.io/docs/usage/models).**

## ⚒ Compile from source

The other way to install spaCy is to clone its
[GitHub repository](https://github.com/explosion/spaCy) and build it from
source. That is the common way if you want to make changes to the code base.
You'll need to make sure that you have a development environment consisting of a
Python distribution including header files, a compiler,
[pip](https://pip.pypa.io/en/latest/installing/),
[virtualenv](https://virtualenv.pypa.io/en/latest/) and
[git](https://git-scm.com) installed. The compiler part is the trickiest. How to
do that depends on your system.

| Platform    |                                                                                                                                                                                                                                                                     |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ubuntu**  | Install system-level dependencies via `apt-get`: `sudo apt-get install build-essential python-dev git` .                                                                                                                                                            |
| **Mac**     | Install a recent version of [XCode](https://developer.apple.com/xcode/), including the so-called "Command Line Tools". macOS and OS X ship with Python and git preinstalled.                                                                                        |
| **Windows** | Install a version of the [Visual C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) or [Visual Studio Express](https://visualstudio.microsoft.com/vs/express/) that matches the version that was used to compile your Python interpreter. |

For more details
and instructions, see the documentation on
[compiling spaCy from source](https://spacy.io/usage#source) and the
[quickstart widget](https://spacy.io/usage#section-quickstart) to get the right
commands for your platform and Python version.

```bash
git clone https://github.com/explosion/spaCy
cd spaCy

python -m venv .env
source .env/bin/activate

# make sure you are using the latest pip
python -m pip install -U pip setuptools wheel

pip install -r requirements.txt
pip install --no-build-isolation --editable .
```

To install with extras:

```bash
pip install --no-build-isolation --editable .[lookups,cuda102]
```

## 🚦 Run tests

spaCy comes with an [extensive test suite](spacy/tests). In order to run the
tests, you'll usually want to clone the repository and build spaCy from source.
This will also install the required development dependencies and test utilities
defined in the [`requirements.txt`](requirements.txt).

Alternatively, you can run `pytest` on the tests from within the installed
`spacy` package. Don't forget to also install the test utilities via spaCy's
[`requirements.txt`](requirements.txt):

```bash
pip install -r requirements.txt
python -m pytest --pyargs spacy
```
