<h1>Project Apple Website</h1>

Generate SSH Key: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=mac

<ul>
    <li>eval "$(ssh-agent -s)"</li>
    <li>ssh-add keygen-yang-private</li>
</ul>

<p>Step untuk push code changes ke github</p>
<ol>
    <li>git status (warna merah artinya file yang changes)</li>
    <li>git add .</li>
    <li>git status (warna hijau, file yang sudah ter-add)</li>
    <li>git commit -m "pesan"</li>
    <li>git push origin main</li>
</ol>

<h2>Author</h2>
<p><b>Andri Deng</b></p>