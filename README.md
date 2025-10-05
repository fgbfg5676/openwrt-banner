# JSON Field Explanation
- "enabled": 是否启用插件，true 表示启用，false 表示禁用（默认 true）
- "disable_message": 当 enabled 为 false 时显示的禁用消息，建议提供简短说明
- "text": 主横幅文本，显示在页面顶部
- "banner_texts": 轮播文本数组，每隔 carousel_interval（默认 5000ms）切换显示
- "color": 横幅背景颜色，支持 "rainbow" 或其他 CSS 颜色值
- "background_1" 到 "background_12": 背景图片 URL，支持 4 组，每组 3 张图片
- "nav_tabs": 导航分组数组，每个分组包含 title 和 links 数组
