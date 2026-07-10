# Architecture — v3.5.0 Friend Design Sprint 1

## Single Friend State

Home / Friend's Form / Message / Voice / Memory / Profile / Guardian は、同じ保存済みFriendStateを参照します。

## Presence Layer

- Continuous breathing: CSS animation
- Natural blink: irregular JavaScript timer
- Quiet glance: irregular JavaScript timer
- Idle motions: MBFLiving state machine
- Living sky: slow CSS animation
- World sprout: Home-only world object

## Accessibility

`prefers-reduced-motion` が有効な場合、呼吸・波紋・雲・芽などの連続アニメーションを停止します。
