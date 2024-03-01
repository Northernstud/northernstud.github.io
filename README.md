<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Project: Blog</title>
        <style>
            body {
                background-color:rgb(224, 217, 168);
                font-family: monospace ;
            }
            h1 {
                font-family: cursive;
            }
            .head {
                font-family: cursive;
            }
            p {
                font-family: cursive;
            }
            .contents {
                text-decoration: none;
            }
            h2 {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        
        <h1>Bach's blog</h1>

        <h3>Contents</h3>
        <ul>
            <li class = "contents"><a href = "#firstPost">First post!</a></li>
            <li class = "contents"><a href = "#secondPost">Second post!</a></li>
        </ul>
        
        <h2 id = "firstPost">First post</h2>
        <h6>3/1/2024</h6>
        
        <p>There are many <em>"blogging engines"</em> out there, like WordPress and Blogger, but in this project, you'll make your own blog using <strong>HTML and CSS</strong>. It should have at least 2 entries, and the table of contents should internally link to each entry. Use CSS text properties to style your blog - like changing the font family, line height, and font styles of various sections.</p>
        <table>
            <thead>
                <tr>
                    <th class = "head">time</th>
                    <th class = "head">to do</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>10am</td>
                    <td>wake up</td>
                </tr>
                <tr>
                    <td>1pm</td>
                    <td>school</td>
                </tr>
            </tbody>
        </table>
        
        <h2 id = "secondPost">Second post</h2>
        <h6>3/2/2024</h6>
        
        <p>A "blog" <em>(or "web log")</em> is an online journal, which one or multiple people update on a frequent basis, like daily, weekly, or monthly. Many new programmers keep blogs to document their journey to becoming a programmer, with updates on what they've learned and what they've made.</p>
        <table>
            <thead>
                <tr>
                    <th class = "head">time</th>
                    <th class = "head">to do</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>9am</td>
                    <td>wake up</td>
                </tr>
                <tr>
                    <td>10am</td>
                    <td>school</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
