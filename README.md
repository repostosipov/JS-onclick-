# JS вкл \ выкл disable 

id='register'
onclick='register.toggleAttribute("disabled")'


Показать \ скрыть пароль

<div class="password">
   <input type="password" class="form-control" name="password" id="password" autocomplete="current-password" placeholder='введите пароль'>
    <a href="#" class="password-control" onclick="return show_hide_password(this);"></a>
    <p class="text-end"><a href="{% url 'account_reset_password' %}">Забыли пароль??</a></p>
</div>
