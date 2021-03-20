# DU004: Modify HTML DOM with Python Selenium

1. Removing lines in with `<script>` tag from html file. This is neccessary to display LinkedIn pages locally, by removing active JavaScript code.

```
sed 's/>/>\n/g' linkedin.html  | grep -v '<script' > no_script.html
```

2. We shall modify the name below the main profile picture (red rectangle) in Figure 1.

- Figure 1
<img src="https://github.com/udexon/DUNIIX/blob/main/img/LinkedIn_JW_rb.png" width=400>


3. The name in Figure 1 is changed, as shown in Figure 2 (red rectangle), with the Python code shown below, run with Selenium driver: 

```python
>>> driver.execute_script("document.getElementsByTagName('li')[21].innerText='mifasolasido'")
```

- Figure 2
<img src="https://github.com/udexon/DUNIIX/blob/main/img/mifaso_rb.png" width=400>

- Figure 3: Python Selenium code to modify DOM.
<img src="https://github.com/udexon/DUNIIX/blob/main/img/mifaso_selenium.png" width=600>

