{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "e7b1b438",
   "metadata": {},
   "source": [
    "Интернет-магазин собирает историю покупателей, проводит рассылки предложений и планирует будущие продажи. Для оптимизации процессов надо выделить пользователей, которые готовы совершить покупку в ближайшие 90 дней.\n",
    "\n",
    "<br>Цель:\n",
    "<br>Предсказать вероятность покупки в течение 90 дней\n",
    "\n",
    "<br>Задачи\n",
    "<br>- Изучить данные\n",
    "<br>- Разработать полезные признаки\n",
    "<br>- Создать модель для классификации пользователей\n",
    "<br>- Обучить модель и найти метрику roc-auc\n",
    "<br>- Выполнить тестирование\n",
    "\n",
    "<br>Данные:\n",
    "<br>apparel-purchases - история покупок\n",
    "<br>- client_id - идентификатор пользователя\n",
    "<br>- quantity - количество товаров в заказе\n",
    "<br>- price - цена товара\n",
    "<br>- category_ids - вложенные категории, к которым отнсится товар\n",
    "<br>- date - дата покупки\n",
    "<br>- message_id - идентификатор сообщения из рассылки\n",
    "\n",
    "<br>apparel-messages - история рекламных рассылок\n",
    "<br>- bulk_campaign_id - идентификатор рекламной кампании\n",
    "<br>- client_id - идентификатор пользователя\n",
    "<br>- message_id - идентификатор сообщений\n",
    "<br>- event - тип события\n",
    "<br>- channel - канал рассылки\n",
    "<br>- date - дата рассылки\n",
    "<br>- created_at - точное время создания сообщения\n",
    "\n",
    "<br>apparel-target_binary - совершит ли клиент покупку в течение следующих 90 дней\n",
    "<br>- client_id - идентификатор пользователя\n",
    "<br>- target - целевой признак"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.19"
  },
  "toc": {
   "base_numbering": 1,
   "nav_menu": {},
   "number_sections": true,
   "sideBar": true,
   "skip_h1_title": false,
   "title_cell": "Table of Contents",
   "title_sidebar": "Contents",
   "toc_cell": false,
   "toc_position": {},
   "toc_section_display": true,
   "toc_window_display": false
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
