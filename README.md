# Regex-Password-Req


Minimum eight characters, at least one letter and one number:

/^(?=.*[A-Za-z])(?=.*\d)[A-Za-z\d]{8,}$/

Minimum eight characters, at least one letter, one number and one special character:

/^(?=.*[A-Za-z])(?=.*\d)(?=.*[@$!%*#?&])[A-Za-z\d@$!%*#?&]{8,}$/

Minimum eight characters, at least one uppercase letter, one lowercase letter and one number:

/^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d]{8,}$/

Minimum eight characters, at least one uppercase letter, one lowercase letter, one number and one special character:

/^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}$/

Minimum eight and maximum 10 characters, at least one uppercase letter, one lowercase letter, one number and one special character:

/^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,10}$/

Source:
https://regexlib.com/(X(1)A(oLiR7jmztW2GFQDYqA7XAh1vfaojvYrBW0IPofJsJ3JFxTTKzef8XKBy6KPzrru9NXPg2itULTZ6lURaOxlOcOE2x2_6tP0CCmMjxu1Jz3Ur9GbFIWOy_vKH_aFlDRHI-lV1-xxHoXWvTLoONKWmGQjo4Z-ZbJXWhdnbSBFdYC2rUWzpV0lBTt2SQAybgGYM0))/Search.aspx?k=password&c=-1&m=-1&ps=20
