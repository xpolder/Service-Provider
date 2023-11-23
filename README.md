# Service-Provider
Classification task. I was required to predict the outflow of clients of a telecommunications company given their personal data
 {
 "cells": [
  {
   "cell_type": "markdown",
   "id": "c0c42643",
   "metadata": {},
   "source": [
    "# Проект для оператора связи"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "37d865f5",
   "metadata": {},
   "source": [
    "Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a6e2bb38",
   "metadata": {},
   "source": [
    "**Описание данных**\n",
    "\n",
    "Данные состоят из файлов, полученных из разных источников:\n",
    "\n",
    "- `contract_new.csv` — информация о договоре;\n",
    "- `personal_new.csv` — персональные данные клиента;\n",
    "- `internet_new.csv` — информация об интернет-услугах;\n",
    "- `phone_new.csv` — информация об услугах телефонии.\n",
    "\n",
    "Во всех файлах столбец `customerID` содержит код клиента.\n",
    "\n",
    "Информация о договорах актуальна на 1 февраля 2020."
   ]
  },
