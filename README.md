# KrabbyPatty3am - Resource

## 共筆
[hackpad](https://hackpad.com/IDEA-BOX-Pmo7Ho8qYKC)

### CYH 三圍
- 81.6 
- 54.4 
- 86.72

###  Git 規範
```
Master
├─ Hotfix
│  └─ Fix Name
│     └ 開發者暱稱 + 日期 (Name-yyyy-mm-dd)
├─ Release
├─ Develop
│  ├─ Feature Name
│  │  └ 開發者暱稱 + 日期 (Name-yyyy-mm-dd)
│  └─ Fix Name
│     └ 開發者暱稱 + 日期 (Name-yyyy-mm-dd)
└─ feature

```
Description
- Master : 正式發佈的成品
	- Hotfix
	    - Fix Name : 修正已發佈至Master上的功能的bug，以功能命名
	        - 開發者暱稱 + 日期 (Name-yyyy-mm-dd)
	- Release : 進行從Develop發佈至Master前的準備動作
	- Develop
	    - Feature Name : 開發的次要支線，依據功能區分，以功能命名
	        - 開發者暱稱 + 日期 (Name-yyyy-mm-dd)
	    - Fix Name : 修正已發佈至Develop上的功能的bug，以功能命名
	        - 開發者暱稱 + 日期 (Name-yyyy-mm-dd)
	- Feature : 保留