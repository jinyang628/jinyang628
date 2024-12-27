<pre>
from datetime import date

from app.models import Engineer

😄 = Engineer(
  "Jin Yang",
  <a href="https://chenjinyang.vercel.app/" rel="noopener noreferrer">portfolio_website</a>,
  <a href="https://www.linkedin.com/in/chen-jin-yang-37baa8202/" rel="noopener noreferrer">linkedin</a>,
  <a href="mailto:chenjinyang4192@gmail.com">email</a>
)

today = date.today()
while not today.day == 32:
  😄.code()
</pre>
