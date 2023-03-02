# test_report
Автоматизация формирования отчётов по резульатам испытаний

Разработка пет-проекта по автоматизации рутинной работы по формированию отчётов испытаний и документации по отчёту. 
Автозаполнение word файла на основе вносимых вводных данных.

Работа с несколькими Word и Excel файлами при помощи Python.

Используемый стек (модули/библиотеки и т.д.:

docx

from docx.shared import Mm, Cm, Pt
from docx.enum.text import WD_ALIGN_PARAGRAPH
from docx.enum.table import WD_ALIGN_VERTICAL

pymorphy2


from pymorphy2.tokenizers import simple_word_tokenize

# импортируем модуль DocxTemplate
from docxtpl import DocxTemplate

# импортируем библиотеку pandas
import pandas as pd

# импортируем библиотеку numpy
import numpy as np

# импортируем datetime
import datetime

# импортируем регулярные выражения
import re

# импортируем модуль os
import os

# импортируем random
import random
