# study-arduino
>[!IMPORTANT]
>ctrl을 누르고 링크를 누르면 새탭에서 열립니다.
>일반적으로는 이 창에 열립니다.


---
### 1. 실습 1
> [!NOTE]
> NOT 게이트의 입력단에 스위치, 출력단에 LED를 각각 연결하는 회로를 설계하고 브레드보드에 구성하고 스위치의 조작에 따라 LED가 켜지는지 관찰한 결과를 기록한다. TinkerCAD 싸이트를 통해 회로를 시뮬레이션하고 그 결과를 정리한다 (아래 모든 실습에 시뮬레이션 결과를 정리한다)

- 팅커캐드 링크: [NOT게이트](https://www.tinkercad.com/things/gGx9682GeXQ-1-1-not?sharecode=0t4Lx8e0nm0ciAFeK0Mgd7AM1751tTWReFJnp6SaoRU)

#### NOT 게이트 출력결과
|입력 (A)|출력 (Q)|
|---|---|
|0|1|
|1|0|
---
### 2. 실습2 
> [!NOTE]
> AND 및 NAND 게이트에 대해 위와 같은 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [AND 게이트](https://www.tinkercad.com/things/bfcF16zJQzM-2-2-and-?sharecode=Du638_YVCLkwGIdkhJysqB1JZx1gNdZlEii6mWgrmAk)   
- 팅커캐드 링크: [NAND 게이트](https://www.tinkercad.com/things/ivBUraxTgrd-2-2-nand-?sharecode=eHfRsVIld4U9eUzQpQ1NOAW9lHACxSQBq0A6cb6vMJ0)

#### AND 게이트 출력결과
|입력 (A)|입력 (B)|출력 (Q)|
|---|---|---|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|
#### NAND 게이트 출력결과
|입력 (A)|입력 (B)|출력 (Q)|
|---|---|---|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|
---
### 3. 실습3 
> [!NOTE]
> OR 및 NOR 게이트에 대해 위와 같은 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [NOR 게이트](https://www.tinkercad.com/things/3eT1znDlYNs-3-3-nor-?sharecode=eFR61rz_a3E31EdqQ6rEqyhsDtLyoYeXYAddIhCFXfU)   
- 팅커캐드 링크: [OR 게이트](https://www.tinkercad.com/things/5xpm7igm7cJ-3-3-or-?sharecode=WhHsBUETNvuTtcxtJdNwIDB2LWLrKSXIjsJXHzdDeEI)

#### OR 게이트 출력결과
|입력 (A)|입력 (B)|출력 (Q)|
|---|---|---|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|1|
#### NOR 게이트 출력결과
|입력 (A)|입력 (B)|출력 (Q)|
|---|---|---|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|0|
---
### 4. 실습4 
> [!NOTE]
> XOR 게이트에 대해 위와 같은 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [XOR 게이트](https://www.tinkercad.com/things/6hHoBDRLq8v-4-4-xor-?sharecode=mQQIOziU85xiiz-64zyO9lnJ31wvqeWTsaiCG1y3frc)

#### XOR 게이트 출력결과
|입력 (A)|입력 (B)|출력 (Q)|
|---|---|---|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|
---
### 5. 실습5 
> [!NOTE]
> 분배법칙 (OR-AND 및 AND-OR)에 대해 위와 같은 회로를 구성하고관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [분배법칙 (AND-OR)](https://www.tinkercad.com/things/8UgdcvaorV9-5-5-and-or-?sharecode=vV-lMW9mlgw4BIhtECggTegYrk3e3tOHa-eAVmOQOPw)   
- 팅커캐드 링크: [분배법칙 (OR-AND)](https://www.tinkercad.com/things/2Vq8YWiamfP-5-5-or-and-?sharecode=gGwHU1-zcpn_VFQRCpIHCJ0fEtFYJ0fGw3DC9ukxGbc)

#### OR-AND 게이트 출력결과
|입력 (A)|입력 (B)|입력 (C)|출력 (X)|출력 (Y)|
|---|---|---|---|---|
|0|0|0|0|0|
|0|0|1|0|0|
|0|1|0|0|0|
|0|1|1|0|0|
|1|0|0|0|0|
|1|0|1|1|1|
|1|1|0|1|1|
|1|1|1|1|1|

#### AND-OR 게이트 출력결과
|입력 (A)|입력 (B)|입력 (C)|출력 (X)|출력 (Y)|
|---|---|---|---|---|
|0|0|0|0|0|
|0|0|1|0|0|
|0|1|0|0|0|
|0|1|1|0|0|
|1|0|0|0|0|
|1|0|1|1|1|
|1|1|0|1|1|
|1|1|1|1|1|
---
### 6. 실습9 
> [!NOTE]
> NOT, NAND, NOR 게이트를 이용한 AND 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [NOT, NAND, NOR 게이트를 이용한 AND게이트](https://www.tinkercad.com/things/1EZOJ8PVFLY-6-9-not-nand-nor-and?sharecode=D1PHRlwH9sfPd-uuqNklv5D3NZN7tJ00k12crJtm2uY)

#### AND 게이트 출력결과
|입력 (A)|입력 (B)|출력 (X)|출력 (Y)|
|---|---|---|---|
|0|0|0|0|
|0|1|0|0|
|1|0|0|0|
|1|1|1|1|
---
### 7. 실습10 
>[!NOTE]
>NAND 게이트를 이용한 XOR 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [NAND 게이트를 이용한 XOR 회로](https://www.tinkercad.com/things/8JGrdyFq6Pe-7-10-nand-xor-?sharecode=cj5FkYHU0KZBgAKm4rZo12KBp_WNqLvl6yrbc8NBWa4)

#### XOR 게이트 출력결과
|입력 (A)|입력 (B)|출력 (X)|
|---|---|---|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|
---
### 8. 실습11
> [!NOTE]
> 출력 X에 대한 진리표를 참고하여 카르노 맵을 작성하여 논리함수를간략화하고, 간략화된 논리회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [출력 X에 대한 진리표를 참고하여 카르노 맵](https://www.tinkercad.com/things/8LBJwiFq7y8-8-11-x-)

#### 출력결과
|입력 (A)|입력 (B)|입력 (C)|출력 (Y)|
|---|---|---|---|
|0|0|0|0|
|0|0|1|0|
|0|1|0|0|
|0|1|1|1|
|1|0|0|0|
|1|0|1|1|
|1|1|0|1|
|1|1|1|1|
---
### 9. 실습13
> [!NOTE]
> 반가산기 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [반가산기 회로](https://www.tinkercad.com/things/fOhwFp0IFSr-9-13-)

|A|B|S|C|
|---|---|---|---|
|0|0|0|0|
|0|1|1|0|
|1|0|1|0|
|1|1|0|1|
---
### 10. 실습14
> [!NOTE]
> 전가산기 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [전가산기 회로](https://www.tinkercad.com/things/eab6LGShKXh-10-14-)

|A|B|Cn-1|S|Cn|
|---|---|---|---|---|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|
---
### 11. 실습15
> [!NOTE]
> 2비트 2진가산기 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [미작성]()

|제목 셀1|제목 셀2|제목 셀3|제목 셀4|
|---|---|---|---|
|내용 1|내용 2|내용 3|내용 4|
|내용 5|내용 6|내용 7|내용 8|
|내용 9|내용 10|내용 11|내용 12|
---
### 12. 실습16
> [!NOTE]
> 2x4 디코더 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [2x4 디코더 회로](https://www.tinkercad.com/things/5RZnzLSjKjQ-12-16-2x4-)

|B|A|Y3|Y2|Y1|Y0|
|---|---|---|---|---|---|
|0|0|0|0|0|1|
|0|1|0|0|1|0|
|1|0|0|1|0|0|
|1|1|1|0|0|0|

---
### 13. 실습18
> [!NOTE]
> 7-세그먼트 디코더 회로를 구성하고 관찰한 결과와 시뮬레이션한 결과를 정리한다.

- 팅커캐드 링크: [미작성]()

|제목 셀1|제목 셀2|제목 셀3|제목 셀4|
|---|---|---|---|
|내용 1|내용 2|내용 3|내용 4|
|내용 5|내용 6|내용 7|내용 8|
|내용 9|내용 10|내용 11|내용 12|
---
