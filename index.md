# Hello, I'm learning Markdown 
## This is cool
### Here's a pic of me learning Markdown
![image of Adeptus Mechanicus](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/ae87168b-d6c4-44ee-8ddc-39f84a8e771e/d8yfc8i-90776bee-e3a7-49a4-83de-d9c73e4cb7a4.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2FlODcxNjhiLWQ2YzQtNDRlZS04ZGRjLTM5Zjg0YThlNzcxZVwvZDh5ZmM4aS05MDc3NmJlZS1lM2E3LTQ5YTQtODNkZS1kOWM3M2U0Y2I3YTQuanBnIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.l5qRmMzWsQ9CmuA5l2CI2RngILk_LbcSZiJuLQUBm18)
## Here's a code block to check palindromes
```
num = int(input("Enter number to reverse:\n"))
absNum = abs(num)
rev = absNum % 10
absNum = absNum // 10
while absNum > 0:
    r = absNum % 10
    absNum = absNum // 10
    rev = rev * 10 + r
if num < 0:
    rev = -rev
if num == rev:
    print("Palindrome")
else:
    print("Not palindrome")
```
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
