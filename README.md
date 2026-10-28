# Surarin's VPM Packages

VRChat Creator Companion（VCC）で Surarin のパッケージを入れるためのリストです。
A VPM listing for installing Surarin's packages with the VRChat Creator Companion (VCC).

## 追加のしかた / How to add

VCC の Settings → Packages → Add Repository に、次の URL を入れます。
In VCC, open Settings → Packages → Add Repository and enter:

```
https://<GitHubのユーザー名>.github.io/SurarinVPM/index.json
```

## パッケージ / Packages

| ID | 名前 / Name |
|---|---|
| `com.surarin.worldtitlegimmick` | World Title Gimmick（ワールド内称号ギミック） |

## 更新のしかた（作者用）

1. WTG_sample の Unity で「World Title Gimmick Dev/配布物を作る」を押す。
2. `Build/Release` の zip を GitHub のリリースに上げる（または `packages/` に置く）。
3. `listing-entry.json` の中身を、`index.json` の `versions` に版の番号で足す（`url` は zip の URL）。
4. コミットして push する。GitHub Pages が `index.json` を公開する。
