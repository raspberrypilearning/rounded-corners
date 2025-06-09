要使元素的角变圆，可以使用 `rounded` 类。

![网页上的三个块，每个都有圆角。](images/rounded.PNG)

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

<div class="rounded">
    <p>在此处添加文本。</p>
</div>

\--- /code ---

\*\*提示：\*\*你可以在 `style.css` 中调整 `rounded` 类的 `border-radius` 。

## --- code ---

language: CSS
filename: style.css
line_numbers: false
--------------------------------------------------------

.rounded {
border-radius: 1rem;
}

\--- /code ---
