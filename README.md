# Описание платежного модуля ИнвойсБокс для WooCommerce 2.0+

Платёжный модуль для интеграции платёжной системы «ИнвойсБокс» и CMS WordPress+WooCommerce. Реализована поддержка платёжного API. Протестировано на системе WooCommerce 2.0+.

Модуль позволяет организовать оплату товаров в магазине через систему «ИнвойсБокс». Система «ИнвойсБокс» позволяет Интернет-магазину принимать оплату через популярные инструменты -
банковские карты, системы Интернет-банка, электронные деньги, терминалы, кассы банков и счета мобильных телефонов. Оплата приходит на расчётный счёт компании или индивидуального предпринимателя.
При работе с «ИнвойсБокс» Интернет-магазину не требуется покупать и обслуживать онлайн-кассу в соответствии с ФЗ-54, чеки для плательщиков «ИнвойсБокс» формирует за Интернет-магазин.

# Установка и настройка модуля ИнвойсБокс на WooCommerce 2.0+

## Установка модуля

1. Убедитесь что у вас установлена посленяя версия плагина [WooCommerce](/www.woothemes.com/woocommerce)
2. Распакуйте архив и загрузите папку "invoicebox-for-woocommerce" в папку ваш-домен/wp-content/plugins
3. Активируйте плагин

## Настройка модуля

После активации плагина через панель управления в WooCommerce в разделе 
<strong>WooCommerce - Настройки - Платежи - INVOICEBOX</strong> необходимо
указать параметры магазина: идентификатор, региональный код и API ключ.
Параметры магазина выдаются при заключении договора, а также их можно
получить в личном кабинете по адресу: https://login.invoicebox.ru

<ul style="list-style:none;">
<li>URL: До версии WooCommerce 2.0 - http://your_domain/?wc-api=wc_invoicebox, в версии WooCommerce 2.0+ http://your_domain/wc-api/wc_invoicebox/</li>
<li>Метод отсылки данных: POST</li>
</ul>
