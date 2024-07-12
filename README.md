# Macbook wasd to arrow and numpad binding

Karabiner-Elements를 이용해 적용할 수 있는 키보드 수정사항이며,
미니배열 키보드에서 영감을 받아 맥북 키보드에서 방향키 및 숫자 입력을 좀 더 편하게 사용할 수 있게 개선합니다.

## 적용 방법

Karabiner-Elements의 Complex Modifications 에서 Add your own rule을 클릭하고 rule.json 파일 내용을 붙여넣습니다.

## 전체 규칙

- 오른 `command + wasd`를 방향키로 변경
- 오른 `command + qe`를 `page up`, `page down`으로 변경
- 오른 `command + fv`를 `home`, `end`로 변경
- `fn + m,.jkluio`, `fn + space` 키를 `numpad`로 변경

## wasd to arrow

맥북에서 방향키를 사용하려면 오른손의 위치를 오른쪽 하단으로 이동해야하며, 방향키를 자주 사용해야할 경우 이로 인해 손목에 피로를 줄 수도 있습니다.

오른손 엄지로 command, 왼손은 타이핑 하던 위치에서 wasd 를 누름으로서 타이핑하던 손의 위치를 크게 벗어나지 않고 방향키를 사용할 수 있습니다.

오른 command와 해당 키들을 조합하는 단축키를 사용할 경우 정상작동 하지 않을 수 있습니다.

- Right command + w => arrow up
- Right command + a => arrow left
- Right command + s => arrow down
- Right command + d => arrow right

## page up, page down, home, end

맥에서 page up, page down, home, end를 사용하려면 fn + arrow 키를 눌러야합니다.

방향키를 사용할 경우 오른 손의 동선이 부자연스러우며, 위의 `wasd to arrow`적용 하더라도 fn + right command + wasd 를 입력해야하기 때문에 복잡합니다.

이를 오른 command + qefv 변경하여 손의 이동 없이 간편하게 사용할 수 있도록 했습니다.

- Right command + q => page up
- Right command + e => page down
- Right command + f => home
- Right command + v => end

## Numpad

맥북에는 numpad가 존재하지 않아서 많은 숫자를 입력해야하는 작업에 불편할 수 있습니다.

fn 조합으로 numpad를 구현해 필요 시 numpad를 사용하는 감각으로 숫자를 입력할 수 있도록 수정했습니다.

- fn + space => numpad 0
- fn + m => numpad 1
- fn + , => numpad 2
- fn + . => numpad 3
- fn + j => numpad 4
- fn + k => numpad 5
- fn + l => numpad 6
- fn + u => numpad 7
- fn + i => numpad 8
- fn + o => numpad 9
- fn + right option => numpad .
