<p align="center"><img src="assets/grey-sit.png" alt="그레이" width="172"></p>

<h1 align="center">Kkurei AI Dashboard · 꾸레이 AI 대시보드</h1>

<p align="center">
Codex·Claude Code 남은 사용량을 한눈에, 바탕화면 고양이 그레이 밑에서.<br>
Your Codex &amp; Claude Code usage at a glance, right under a desktop cat.
</p>

<p align="center">
<a href="https://github.com/pcs3013/kkurei-ai-dashboard/releases/latest"><img alt="release" src="https://img.shields.io/github/v/release/pcs3013/kkurei-ai-dashboard"></a>
<a href="https://github.com/pcs3013/kkurei-ai-dashboard/releases"><img alt="downloads" src="https://img.shields.io/github/downloads/pcs3013/kkurei-ai-dashboard/total"></a>
<img alt="platforms" src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey">
<img alt="price" src="https://img.shields.io/badge/price-free-brightgreen">
</p>

<p align="center">
<a href="https://kkurei.com/dashboard/"><b>한국어 안내 · 설치 방법</b></a> ·
<a href="https://kkurei.com/en/dashboard/"><b>English guide</b></a>
</p>

---

## 한국어

작업하다 한도가 얼마나 남았는지 궁금할 때 창을 오가지 않아도 돼요.

- **AI Usage Dashboard**: Codex·Claude Code의 5시간·주간 남은 사용량과 리셋까지 남은 시간을 보여 줘요.
- **Kkurei Free**: 바탕화면을 돌아다니는 고양이 그레이. 고르면 그레이 밑에 남은 양 게이지가 떠요. 남은 양이 20·15·10·5%가 되면 말풍선으로 알려 줘요.
- 계정이 여러 개면 대시보드에서 계정을 더해 각각 볼 수 있어요 (Mac).
- 무료이고 회원가입이 없어요. 사용량은 이 컴퓨터 안에서만 쓰고 꾸레이 서버로 보내지 않아요.

### 다운로드

[**Releases**](https://github.com/pcs3013/kkurei-ai-dashboard/releases/latest)에서 내 컴퓨터에 맞는 ZIP을 받으세요.

| 운영체제 | 파일 | 필요한 것 |
|---|---|---|
| Mac | `Kkurei-AI-Dashboard-mac-v*.zip` | macOS 14 이상 (Apple Silicon · Intel) |
| Windows | `Kkurei-AI-Dashboard-win-v*.zip` | Windows 10·11 64비트 + Python 3.10 이상(Tcl/Tk 포함) · 미리보기 |

- 두 파일 모두 Apple·Microsoft의 서명을 받지 않았어요. 처음 열 때 경고가 뜨면 [설치 안내](https://kkurei.com/dashboard/)를 따라 확인하세요.
- 받은 파일은 릴리스의 `.sha256` 값과 비교해 확인할 수 있어요. (Mac: `shasum -a 256 파일명` · Windows PowerShell: `Get-FileHash 파일명`)
- Codex·Claude Code를 쓰려면 각 CLI를 설치하고 로그인해야 해요. 자세한 방법은 안내 페이지에 있어요.

### 알려진 한계

- Windows판은 미리보기예요. 계정 여러 개 추가는 Mac판에만 있고, Claude Code 사용량은 Claude Code를 쓰는 동안 갱신돼요.
- 이 앱은 OpenAI 또는 Anthropic의 공식 앱이 아닌 별도 제작 앱이에요.
- 이 저장소에는 설명서와 배포 파일만 있어요. 소스 코드는 공개하지 않아요.

### 문의 · 제안

[Issues](https://github.com/pcs3013/kkurei-ai-dashboard/issues)에 남겨 주세요. 비밀번호·인증 토큰·로그인 파일은 올리지 마세요.

---

## English

Check how much of your Codex and Claude Code limits remain without switching windows.

- **AI Usage Dashboard** shows the 5-hour and weekly remaining usage and the time until reset.
- **Kkurei Free** is a free desktop cat, Grey. Pick the limits you want and they appear as small gauges under the cat, with a speech bubble at 20, 15, 10 and 5% remaining.
- Several accounts? Add them in the dashboard (Mac).
- Free, no sign-up. Usage values stay on your computer and are not sent to Kkurei servers.

### Download

Get the ZIP for your computer from [**Releases**](https://github.com/pcs3013/kkurei-ai-dashboard/releases/latest).

| OS | File | Requires |
|---|---|---|
| Mac | `Kkurei-AI-Dashboard-mac-v*.zip` | macOS 14+ (Apple Silicon and Intel) |
| Windows | `Kkurei-AI-Dashboard-win-v*.zip` | Windows 10/11 64-bit + Python 3.10+ with Tcl/Tk · preview |

- Neither ZIP is signed or notarized by Apple or Microsoft, so a warning may appear on first launch. See the [install guide](https://kkurei.com/en/dashboard/).
- Verify the download against the `.sha256` file in the release (Mac: `shasum -a 256 file` · Windows PowerShell: `Get-FileHash file`).
- Codex and Claude Code CLIs must be installed and signed in. Details are in the guide.

### Known limits

- The Windows build is a preview. Adding several accounts is Mac-only; Claude Code usage refreshes while you use Claude Code.
- Not an official OpenAI or Anthropic app.
- This repository contains documentation and release files only. The source code is not published.

### Feedback

Please use [Issues](https://github.com/pcs3013/kkurei-ai-dashboard/issues). Never post passwords, tokens or login files.

---

<p align="center"><a href="https://kkurei.com/">꾸레이 오락실</a> · <a href="https://kkurei.com/tools/">꾸레이 툴즈</a> · <a href="https://mydongseon.com/">동선</a></p>
