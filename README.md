## Quiz de programación I
**Instrucción:**
Desarrolla un programa que valide si una contraseña ingresada por el usuario cumple con los siguientes criterios de seguridad:

- Debe tener al menos 8 caracteres
- Debe contener al menos una letra mayúscula
- Debe contener al menos una letra minúscula
- Debe contener al menos un número
- Debe contener al menos un carácter especial (@, #, $, %, &, *)
El programa debe indicar cuáles criterios no se cumplen.

`Nota: Acá te dejo una ayuda.`
(c == '@' || c == '#' || c == '$' || c == '%' || c == '&' || c == '*')
la idea es pedirle al usuario por teclado que ingrese su contraseña que con un condicional, el condicional nos ayudara a que se valide la informacion. se puede hacer una condicion para cada signo, y que se vaya validando los criterios para los 8 caracteres le  decimos que tiene que ser un numero mayor que cero y menor que mil millones, para la letra mayuscula 