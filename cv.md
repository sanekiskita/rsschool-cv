## Шевелев Александр

## контакты
:mailbox_closed: Почта:as1405503@gmail.com     
:pager: Telegram: [@sanek_nyst](https://t.me/sanek_nyst)

## Цель
 усовершенствовать свои навыки и найти работу.

## языки программирования
c++ c#, javascript, SQL, HTML, PHP. Изучал методологию agile.

## Отрывок программы:

 ```
  public void pictureBox_Paint(object sender, PaintEventArgs e)
            {
                e.Graphics.Clear(Color.Black);
                Pen p1 = new Pen(Color.Red, width: 10);
                Pen p = new Pen(Color.Green, width: 20);
                Pen p2 = new Pen(Color.Yellow, width: 5);
                Pen p3 = new Pen(Color.Blue, width: 2);

                for (int i = 0; i < n2; i = 1 + i)
                {
                    for (int j = 0; j < n2; j = 1 + j)
                        if (mtx[i + j * n2] == 1)
                        {
                            e.Graphics.DrawLine(p1, pos[i * 2], pos[i * 2 + 1], pos[j * 2], pos[j * 2 + 1]);//линии
                        }
                }


                for (int i = 0; i <= n2 * 2 - 1; i = i + 2)
                {
                    e.Graphics.DrawEllipse(p, pos[i] - 10, pos[i + 1] - 10, 20, 20);// создание кружков
                }

                //выделение круга фикс
                if (sel >= -1)
                {
                    for (int i = 0; i < n2; i++)
                    {
                        int dx = x - pos[i * 2];
                        int dy = y - pos[i * 2 + 1];
                        if (dx * dx + dy * dy <= 20 * 20)
                        {
                            e.Graphics.DrawEllipse(p2, pos[i * 2] - 20, pos[i * 2 + 1] - 20, 40, 40);//желтый
                            break;
                        }

                    }
                }
                //выделение круга при удалении
                if (yx >= 0 || vid == 1)
                {
                    e.Graphics.DrawEllipse(p3, pos[yx * 2] - 20, pos[yx * 2 + 1] - 20, 40, 40);//синий
                    vid = 1;
                }
            }
```

## Опыт
Есть опыт работы в создании сайта с подключением базы данных без использования CMS.

## Образование
Среднее профессиональное образование по специальности. 09.02.03 (2020г.)

## Английский
Уровень знания английского:Intermediate.
