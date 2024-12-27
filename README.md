<pre>
from datetime import date

from app.models import Engineer

😄 = Engineer(
  "Jin Yang",
  <a href="https://chenjinyang.vercel.app/" target="_blank">portfolio_website</a>,
  <a href="https://www.linkedin.com/in/chen-jin-yang-37baa8202/" target="_blank">linkedin</a>,
  <a href="mailto:chenjinyang4192@gmail.com">email</a>
)

today = date.today()
while not today.day == 32:
  😄.code()
</pre>
