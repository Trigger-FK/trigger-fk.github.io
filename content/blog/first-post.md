+++
title = "IROS2025"
description = "IROS2025参加記"
date = "2025-10-10"
author = "Fumiya Matsuzaki"
+++

# 参加するまでの経緯

最初に断っておくと。僕はロボティクスの人間でもないし、論文を投稿していたわけでもなく。

指導教員の先生から「今年のIROSは中国で開催されてて、松崎君は参加費無料なので、もし興味があれば参加してみてもいいですよ」とお声がけをいただいたので、うきうきマンボーで参加表明をした。

なぜ参加費が無料かというと、今年4月から[IEEE RAS TC on Robot Control](https://ieee-ras-robot-control.github.io/)で学生代表をやっていて、ICRA2025で運営側のお手伝いをしたから。[Welcome Kit](https://docs.google.com/presentation/d/1Ohw3v87uaxTovjM5RM9Y7Zu2lP5NYKsi5BiZnN7FxTI/edit?usp=sharing)なるものを一人で作成しました。

あと、僕の研究の興味は「制御理論側からロボティクスへのアプローチ」というのもあり、トップカンファで情報を集めるのにも絶好の機会だったということ。

## Adding Images

### Method 1: Using static folder (Recommended)

Place your image in `/static/images/blog/` and reference it like this:

```markdown
![Image description](/images/blog/your-image.jpg)
```

Example:
![Example Image](/images/avatar.jpg)

### Method 2: Using external URL

```markdown
![Image description](https://example.com/image.jpg)
```

### Method 3: HTML for more control

```html
<img src="/images/blog/your-image.jpg" alt="Description" width="500">
```

Example with centered image:
<div style="text-align: center;">
  <img src="/images/avatar.jpg" alt="Avatar" width="300">
</div>

## What You Can Do

You can use various Markdown features:

- **Bold text**
- *Italic text*
- Lists
- Links
- Images
- Code blocks

## Example Code

```python
def hello_world():
    print("Hello, World!")
```

## Headings

You can use headings from H1 to H6 to structure your content.

### Subsection Example

This is a subsection under the main heading.

## Image in Headings

You can also include images next to headings:

### 📸 Section with Emoji

Or use HTML for inline images in headings (though not always recommended):

## Conclusion

Feel free to create more blog posts by adding new `.md` files in the `content/blog/` directory!
