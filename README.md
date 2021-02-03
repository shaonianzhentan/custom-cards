# custom-cards
我使用收藏的自定义卡片

## 3.4.1
https://github.com/custom-cards/button-card

## 1.0.0
https://github.com/custom-cards/favicon-counter

## v0.6.3
https://github.com/denysdovhan/purifier-card

```yaml
type: 'custom:purifier-card'
entity: fan.xiaomi_miio_device
stats:
  - attribute: filter_life_remaining
    unit: '%'
    subtitle: 剩余使用量
  - attribute: motor_speed
    unit: RPS
    subtitle: 运行速度
actions:
  - name: Silent
    icon: 'mdi:weather-night'
    speed: Silent
  - name: 25%
    icon: 'mdi:circle-slice-2'
    speed: Favorite
    xiaomi_miio_favorite_level: 3
  - name: 50%
    icon: 'mdi:circle-slice-4'
    speed: Favorite
    xiaomi_miio_favorite_level: 7
  - name: 75%
    icon: 'mdi:circle-slice-6'
    speed: Favorite
    xiaomi_miio_favorite_level: 10
  - name: 100%
    icon: 'mdi:circle-slice-8'
    speed: Favorite
    xiaomi_miio_favorite_level: 14
  - name: Auto
    icon: 'mdi:brightness-auto'
    speed: Auto
show_name: true
show_state: true
show_toolbar: true
compact_view: false
```