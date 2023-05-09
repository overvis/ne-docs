# RNPP-311M MULTIFUNCTIONAL THREE PHASE VOLTAGE MONITORING RELAY. OPERATING MANUAL

![RNPP-311M](RNPP-311M/Device.png)

Quality control system on the development and production complies with requirements ISO 9001:2015

---

**Dear customer!**

**Company NOVATEK-ELECTRO Ltd. thanks you for purchasing our products. You will be able to use properly the product after carefully studying the Operating Manual. Keep the Operating Manual throughout the service life of the product. Review the Operating manual before using the unit. This unit is safe for use in case of compliance with operating rules.**

---

:warning: **ATTENTION! ALL REQUIREMENTS OF THIS OPERATING MANUAL ARE COMPULSORY TO BE MET!** – PRODUCT TERMINALS AND INTERNAL COMPONENTS ARE UNDER POTENTIALLY LETHAL VOLTAGE TO ENSURE THE PRODUCT SAFE OPERATION **IT IS STRICTLY FORBIDDEN THE FOLLOWING:**

- TO CARRY OUT MOUNTING WORKS AND MAINTENANCE WITHOUT DISCONNECTING THE PRODUCT FROM THE MAINS;\*\*
- TO OPEN AND REPAIR THE PRODUCT INDEPENDENTLY;
-  TO OPERATE THE PRODUCT WITH MECHANICAL DAMAGES OF THE CASE.

IT IS NOT ALLOWED WATER PENETRATION ON TERMINALS AND INTERNAL ELEMENTS OF THE PRODUCT.

During operation and maintenance the regulatory document requirements must be met, namely:

- Regulations for Operation of Consumer Electrical Installations;
- Safety Rules for Operation of Consumer Electrical Installations;
- Occupational Safety when in Operation of Electrical Installations.

**ATTENTION! THE DEVICE IS NOT INTENDED TO BE USED FOR LOAD COMMUTATION IN CASE OF SHORT CIRCUITS. THEREFORE OUTPUT CONTACTS OF LOAD RELAY SHOULD BE PROTECTED BY AUTOMATIC CIRCUIT BREAKERS (FUSES) WITH TRIPPING CURRENT NOT EXCEEDING 6.3 A OF CLASS B.**

**To improve operational properties of the unit it is recommended to install the fuse (fuse element), or the equivalent for current of 1A in power supply circuit (L1, L2, L3) for RNPP-311M.**

Installation, adjustment and maintenance of the product must be performed by qualified personnel having studied this Operating Manual.

**In compliance with the requirements of this Operating Manual and regulations the product is safe for use.**

---

![Органы управления и габариты](RNPP-311M/image%201.png)

**Figure 1** - Control descriptions and dimensions diagram

1. Input terminals 400 V / 415 V;
2. Switch of voltage of controlled mains **(400 V / 415 V)**;
3. Switch of protection operation at phase sequence **(SEQ)** (in position “OFF” – the protection is disabled);
4. – Switch of protection operation at voltage imbalance **(IMB)** (in position “OFF” – the protection is disabled);
5. Switch of protection operation at the minimum voltage **(Umin)** (in position “OFF” – the protection is disabled);
6. – Switch of protection operation at the maximum voltage **(Umax)** (in position “OFF” – the protection is disabled);
7. Green LED indicators of voltage presence on each phase **(LINE)**;
8. Red LED **(ALARM)** indicator showing also the open state of the output contacts;
9. Output terminals;
10. Control of setting the protection operation time **(Тoff(sec))**;
11. Control of setting the AR time **(Ton(sec))**;
12. Control of setting the threshold for maximum / minimum voltage **(Unom±%)**.

This operation manual is intended for description, principle of work, construction, mode of work and maintenance of the multifunctional three phase voltage monitoring relay (hereinafter RNPP-311M).

The product meets the requirements of the following:

- EN 60947-1;
- EN 60947-6-2;
- EN 55011;
- EN 61000-4-2.

_Harmful substances, in more than allowed concentration, are not available._

**Terms and abbreviations:**

- **AR** is automatic reclosing;
- **MS** is magnetic starter;

The term **"Normal voltage"** means that the voltage value does not exceed the threshold limit values set by the User.

## 1 APPLICATION

**1.1** RNPP-311M is designed:

- for monitoring the permissible voltage level;
- for monitoring the correct alternation and absence of sticking of phases;
- for monitoring the full-phase and symmetry of the mains voltage (phase imbalance);
- to disconnect the load in case of improper mains voltage;
- for monitoring the quality of the mains voltage after switching off the load and automatically turning it on after restoring the voltage parameters;
- to indicate the failure in the event of emergency situation and the presence of voltage in each phase.

RNPP-311M performs zero control, indirectly. The device provides the possibility of adjusting the parameters (voltage threshold, time of automatic reclosing and time delay of protection operation), selection of the voltage of the monitored mains (400 V or 415 V) and a set of protective functions.

After restoring the voltage parameters of the mains, the device enables again the load after the reclosing time.

**Note - For networks with a high level of harmonics, we recommend using the modification of the RNPP-311M-24 device with the connection to self-contained 24 V power supply.**

**1.2** Operation conditions

The product is designed for operation in the following conditions:

- Ambient temperature: from minus 35 to +55°C;
- Atmospheric pressure: from 84 to 106.7 kPa;
- Relative air humidity (at temperature of +25 °C): 30 … 80%.

_If the temperature of the product after transportation or storage differs from the environment temperature at which it is expected to operate, then before connection to electric mains keep the product under the operating conditions within two hours (because the product elements may have moisture condensation)._

**ATTENTION! The product is not intended for operation in the following conditions:**

- Significant vibration and shocks;
- High humidity;
- Aggressive environment with content in the air of acids, alkalis, etc., as well as severe contaminations (grease, oil, dust, etc.).

**2. TECHNICAL CHARACTERISTICS**

**Table 1**

**Table 2**

**3. INTENDED USE**

**3.1 Preparation for operation**
**3.1.1** Preparation for connection:

- Unpack and check the product for damage after transportation; in case of such damages detection, contact the supplier or manufacturer;
- Carefully study the Operating Manual **(pay special attention to the connection diagram to power the product)**;
- If you have any questions regarding the installation of the product, please contact the manufacturer by telephone number indicated at the end of this Operating Manual.

**3.1.2 Device connection**

**ATTENTION! ALL CONNECTIONS MUST BE PERFORMED WHEN THE PRODUCT IS DE-ENERGIZED.**

**Error when performing the installation works may damage the product and connected devices.** To ensure the reliability of electrical connections you should use flexible (stranded) wires with insulation for voltage of no less than 450 V, the ends of which it is necessary to be striped of insulation for 5±0.5 mm and tightened with bootlaces. Recommended cable cross section for connection is not less 1 mm2. Wires fastening should exclude mechanical damage, twisting and abrasion of the wire insulation.

**IT IS NOT ALLOWED TO LEAVE EXPOSED PORTIONS OF WIRE PROTRUDING BEYOND THE TERMINAL BLOCK.**

**For a reliable contact, tighten the terminal screws with the force indicated in Table 1.** When reducing the tightening torque, the junction point is heated, the terminal block may be melted and wire can burn. If you increase the tightening torque, it is possible to have thread failure of the terminal block screws or the compression of the connected wire.

**3.1.2.1** Connect the device according to the diagram shown in Fig. 2.

**Figure 2** - RNPP-311M Connection diagram

**Notes:**

- If on the first start up RNPP-311M doesn’t allow to turn ON the power load and indicates wrong phase sequence alarm but the user is absolutely sure that the phase sequence is correct – then it is necessary to exchange the wires connected to terminals **10 and 11**.
- If RNPP-311M is being used as a **maximal voltage protection relay** then the break in the magnetic starter coil power circuit should be connected to terminals **1-2 (4-5)** (the reverse logic of switching-on). The switch **Umax** (it. 6, Fig. 1) should be set to ON position (enabled) and the switches **SEQ**, **IMB** and **Umin** should be set to the OFF position (disabled).

**3.1.2.2** Using the **Unom ±%** control (it. 12, Fig. 1), set the required operation threshold for the maximum and minimum voltage as a percentage of the rated supply voltage of the mains.

**Attention! When setting the lower threshold for Umin, the release voltage of the MS must be taken into account.**

**3.1.2.3** Using the Toff (sec) control (it. 10, Fig. 1), set the protection operation time at the maximum voltage and phase imbalance.

**3.1.2.4** Using **Ton(sec)** control (it. 11, Fig. 1) set the reclosing time AR. **Ton(sec)** is the time of automatic reclosing after the device operation and restoration of the mains voltage parameters; on-time is after the rated voltage supply to the device. It is recommended to set the reclosing time AR for air conditioners, refrigerators and other compressor equipment at least 180 - 240 seconds.

**ATTENTION! In order not to break or turn the control, please do not use excessive force when performing the setting operations.**

**3.1.2.5** Enable the necessary protections using protection switches (it. 3 – 6, Fig. 1).
**3.1.2.6** Set the type of mains used with switch of rated voltage of **400 V / 415 V** (it. 2, Fig. 1).
**3.1.2.7** Feed the supply voltage to the terminals of the device.

**3.2 Operation**

**3.2.1** It is possible to adjust the RNPP-311M to operate in following modes:

- “Minimum / maximum voltage control";
- “Minimum voltage control";
- “Maximum voltage control";
- "Phases presence control";
- "Control of incorrect phase sequence and presence of phase sticking";
- "Phase imbalance control".

_Notes: - The control of phases presence is maintained in any operating mode; - In all operating modes, except for the “Maximum voltage control” mode, the product is activated when the phases are broken or the voltage drops below 100 V on one or several phases for a fixed time of 0.2 s._

In “Minimum / maximum voltage control" mode, when the voltage value of the mains is exceeded for the thresholds set by the User, the protected equipment will be disconnected from the mains and red ALARM LED indicator will turn ON .
In “Minimum voltage control" mode, when the mains voltage drops below the threshold set by the User, the protected equipment is disconnected from the mains and red ALARM LED indicator will turn ON.
In “Maximum voltage control" mode, when the mains voltage rises above the threshold set by the User, the protected equipment is disconnected from the mains and red ALARM LED indicator will turn ON.
In "Phases presence control" mode, if one phase is broken, when one of the LINE LED indicators will turn OFF, the protected equipment is disconnected from the mains. Red ALARM LED indicator will turn ON.
In "Control of incorrect phase sequence and presence of phase sticking" mode, if the connection is incorrect or if one of the phases is sticking, one of the LINE LED indicators lights up on the front panel of the device, the ALARM LED indicator will turn ON and the protected equipment disconnects from the mains.
In "Phase imbalance control" mode, in case of voltage imbalance, two LINE LED indicators flash alternately on the front panel of the device, the ALARM LED indicator will turn ON and the protected equipment disconnects from the mains.

\* - ясли переключатель **Umin** находится в положении «Включено», фиксированное время срабатывания изделия составит 12 с.

\*\* - при работе в режиме «Контроль максимального напряжения» время готовности составляет 0,3 с

## 3 ИСПОЛЬЗОВАНИЕ ПО НАЗНАЧЕНИЮ

**3.1 Подготовка к использованию**

**3.1.1** Подготовка к подключению:

- распаковать и проверить изделие на отсутствие повреждений после транспортировки, в случае обнаружения таковых обратиться к поставщику или производителю;
- внимательно изучить Руководство по эксплуатации (обратите особое внимание на схему подключения питания изделия);
-  если у Вас возникли вопросы по монтажу изделия, пожалуйста, обратитесь в отдел технической поддержки по телефону, указанному в конце Руководства по эксплуатации.

**3.1.2 Подключение изделия**

**ВНИМАНИЕ! ВСЕ ПОДКЛЮЧЕНИЯ ДОЛЖНЫ ВЫПОЛНЯТЬСЯ ПРИ ОБЕСТОЧЕННОМ ИЗДЕЛИИ.**

_Ошибка при выполнении монтажных работ может вывести из строя изделие и подключенные к нему приборы._

Для обеспечения надежности электрических соединений следует использовать гибкие (многопроволочные) провода с изоляцией на напряжение не менее 450 В, концы которых необходимо зачистить от изоляции на 5±0,5 мм и обжать втулочными наконечниками. Рекомендуется использовать провод сечением не менее 1 мм2. Крепление проводов должно исключать механические повреждения, скручивание и стирание изоляции проводов.

**НЕ ДОПУСКАЕТСЯ ОСТАВЛЯТЬ ОГОЛЕННЫЕ УЧАСТКИ ПРОВОДА, ВЫСТУПАЮЩИЕ ЗА ПРЕДЕЛЫ КЛЕММНИКА.**

**Для надежного контакта необходимо производить затяжку винтов клеммника с усилием, указанным в таблице 1.**

При уменьшении момента затяжки – место соединения нагревается, может оплавиться клеммник и загореться провод. При увеличении момента затяжки – возможен срыв резьбы винтов клеммника или пережимание подсоединенного провода.

![Схема подключения RNPP-311M](RNPP-311M/image%202.png)

**Рисунок 2** – Схема подключения RNPP-311M

**3.1.2.1** Подключить изделие согласно схеме, указанной на рисунке 2.

**3.1.2.2** Регулятором **Unom±%** (поз.12 рис.1) установить необходимый порог срабатывания по максимальному и минимальному напряже-нию в процентах от номинального напряжения питания сети.

**Внимание! При установке нижнего порога по Umin должно учитываться напряжение отпускания МП.**

**3.1.2.3** Регулятором **Toff (sec)** (поз.10 рис. 1) установить время срабатывания защиты по максимальному напряжению и по перекосу фаз.

**3.1.2.4** Регулятором **Ton(sec)** (поз.11 рис. 1) установить время АПВ.

Ton(sec) – время автоматического повторного включения после срабатывания изделия и восстановления параметров сетевого напряжения; время включения после подачи на изделие нормального напряжения.

Время АПВ рекомендуется устанавливать для кондиционеров, холодильников и других компрессорных приборов не менее 180 – 240 секунд
.

**ВНИМАНИЕ! Не прилагайте чрезмерных усилий при выполнении установочных операций.**

**3.1.2.5** Переключателями срабатывания защиты (поз.3 – 6 рис. 1) включить необходимые защиты.

**3.1.2.6** Переключателем **400 V/415 V** (поз. 2 рис. 1) установить тип используемой сети.

**3.1.2.7** Подать напряжение питания на клеммы изделия.

**Примечания:**

1. Если при первом включении RNPP-311M индицирует аварию по чередованию фаз, а Пользователю заведомо известно, что в сети правильное чередование фаз, необходимо провода, подсоединенные к клеммам **10** и **11**, поменять местами.
2. Если изделие планируется использовать в режиме «Контроль максимального напряжения» (п. 3.2.1.3), разрыв питания катушки МП необходимо подключить к клеммам 1-2 (4-5) (обратная логика включения). Переключатель **Umax** (поз.6 рис. 1) переместить в положение “Включено”, а переключатели **SEQ, IMB, Umin** – в положение «OFF».

**3.2 Использование изделия**

**3.2.1** RNPP-311M может работать в различных режимах:

- Контроль минимального / максимального напряжения;
- Контроль минимального напряжения;
- Контроль максимального напряжения;
- Контроль наличия фаз;
- Контроль неправильного чередования и наличия слипания фаз;
- Контроль перекоса фаз;

**Примечания:**

1. Контроль наличия фаз сохраняется в любом режиме работы;
2. Во всех режимах работы, кроме режима «Контроль максимального напряжения», изделие срабатывает при обрыве фаз или понижении напряжения ниже 100 B на одной или нескольких фазах за фиксированное время 0,2 с.

**3.2.1.1** В режиме «Контроль минимального / максимального напряжения» при выходе значения напряжения сети за пороги, заданные Пользователем, защищаемое оборудование отключится от сети, на лицевой панели изделия загорится индикатор **ALARM**.

**3.2.1.2** В режиме «Контроль минимального напряжения» при понижении напряжения сети ниже порога, заданного Пользователем, защищаемое оборудование отключится от сети, на лицевой панели изделия загорится индикатор **ALARM**.

**3.2.1.3** В режиме «Контроль максимального напряжения», когда напряжение сети повышается выше порога, заданного Пользователем, защищаемое оборудование отключится от сети, на лицевой панели изделия загорится индикатор **ALARM**.

**3.2.1.4** В режиме «Контроль наличия фаз» при обрыве одной из фаз, гаснет один из индикаторов **LINE**, защищаемое оборудование отключится от сети, на лицевой панели изделия загорится индикатор **ALARM**.

**3.2.1.5** В режиме «Контроль неправильного чередования и наличия слипания фаз» при неправильном подключении или при наличии слипания одной из фаз, на лицевой панели изделия поочередно светится один из индикаторов **LINE**, загорится индикатор **ALARM** іи защищаемое оборудование отключится от сети.

**3.2.1.6** В режиме «Контроль перекоса фаз» при перекосе фаз на лицевой панели изделия поочерёдно мигают два индикатора **LINE**, загорится индикатор **ALARM** и защищаемое оборудование отключится от сети.

**3.2.3** После подачи питания на клеммы изделия загораются индикаторы **LINE**. Изделие переходит в состояние выдержки времени АПВ (задается регулятором **Ton(sec)**), при этом мигает индикатор **ALARM**. По окончании отсчета времени АПВ индикатор **ALARM** отключается и RNPP-311M подключает защищаемое оборудование к сети.

**3.2.4** Если изделие используется в режиме «Контроль максимального напряжения», при нормальном напряжении в сети, реле нагрузки отключено (контакты 1-2 (4-5) замкнуты, а контакты 2-3 (5-6) разомкнуты). Это сделано для того, чтобы изделие в режиме «Контроль максимального напряжения» никогда не сработало по понижению напряжения.

В этом режиме при первом включении изделия в сеть значение времени АПВ (**Ton(sec)**) не учитывается.

**ВНИМАНИЕ! Данный режим не рекомендуется использовать с нагрузками типа: двигатели, компрессоры, трехфазные трансформаторы и т.д.**

**3.2.5** Варианты состояния индикаторов **LINE** и **ALARM** приведены в таблице 2.

**Таблиця 2** – Варианты состояния индикаторов LINE и ALARM

![Варианты состояния индикаторов](RNPP-311M/Tab%202.png)

**Примечание** – Авария индицируется в порядке приоритета:

1. обрыв фаз или понижение напряжения ниже 100 В (наивысший приоритет;
2. чередование фаз;
3. минимальное и максимальное напряжение;
4. перекос фаз.

**3.3 Примеры использования RNPP-311M**

**3.3.1** RNPP-311M в режиме «Контроль минимального напряжения»:

- переключатель **Umin** находится в положении “Включено»;
- переключатели **IMB, Umax** находятся в положении «OFF».

Если авария произошла по Umin, изделие сработает через время **Toff (sec)**, установленное Пользователем, загорится красный индикатор **ALARM**, погаснет соответствующий индикатор (индикаторы) **LINE**. При понижении напряжения ниже 100 В изделие сработает через 0,2 с.

**3.3.2** RNPP-311M в режимах «Контроль минимального / максимального напряжения» и «Контроль наличия фаз»

Переключатели **Umin** і **Umax** находятся в положении “Включено”. RNPP-311M сработает при повышении напряжения выше установленного порога через время Toff (sec), а при понижении – с фиксированной задержкой 12 с (отстройка от пусковых просадок), загорится красный индикатор **ALARM**. При обрыве фаз изделие сработает через время 0,2 с.

**3.3.3** RNPP-311M в режиме «Контроль максимального напряжения»:

- переключатель **Umax** находится в положении “Включено;
- переключатели **SEQ,** **IMB,** **Umin** находятся в положении «OFF», индикатор **ALARM** не светится.

Если произошла авария по Umax, изделие сработает через (Toff (sec) + 0,4) с, загорится красный индикатор **ALARM.**

**3.3.4** Время с задержкой на включение
Переключатели **Umin** і **Umax** находятся в положении «OFF».

Реле нагрузки включится после отсчета времени АПВ, установленного Пользователем при помощи регулятора **Ton(sec).** Во всех режимах работы включение/выключение защиты по нарушению порядка чередования фаз осуществляется переключателем **SEQ,** а включение / выключение защиты по перекосу фаз – переключателем **IMB.** При обрыве фаз или снижении напряжения ниже 100 В на одной или более фазах, изделие сработает (выключится), индикатор соответствующей фазы погаснет.

Если переключатели **Umin,** **Umax,** **SEQ,** **IMB** находятся в положении “Включено” и авария произошла по Umin – изделие сработает с фиксированной задержкой 12 секунд (отстройка от пусковых просадок).

## 4 ТЕХНИЧЕСКОЕ ОБСЛУЖИВАНИЕ

**4.1 Меры безопасности**

:warning:**НА КЛЕММАХ И ВНУТРЕННИХ ЭЛЕМЕНТАХ ИЗДЕЛИЯ ПРИСУТСТВУЕТ ОПАСНОЕ ДЛЯ ЖИЗНИ НАПРЯЖЕНИЕ.**

**ПРИ ТЕХНИЧЕСКОМ ОБСЛУЖИВАНИИ НЕОБХОДИМО ОТКЛЮЧИТЬ ИЗДЕЛИЕ И ПОДКЛЮЧЕННЫЕ К НЕМУ УСТРОЙСТВА ОТ ПИТАЮЩЕЙ СЕТИ.**

**4.2** Техническое обслуживание изделия должно выполняться **квалифицированными специалистами.**

**4.3** Рекомендуемая периодичность технического обслуживания – **каждые шесть месяцев.**

**4.4 Порядок технического обслуживания:**

1. проверить надежность подсоединения проводов, при необходимости – зажать с усилием, указанным в таблице 1;
2. визуально проверить целостность корпуса, в случае обнаружения трещин и сколов изделие снять с эксплуатации и отправить на ремонт.
3. при необходимости протереть ветошью лицевую панель и корпус изделия.

**Для чистки не используйте абразивные материалы и растворители.**

**4.5** При обнаружении неисправности изделия отключить питание и проверить правильность подключения. Если выявить неисправность не удалось, снять изделие с эксплуатации и обратиться к производителю.

## 5 СРОК СЛУЖБЫ И ГАРАНТИЯ ИЗГОТОВИТЕЛЯ

**5.1** Срок службы изделия 10 лет. По истечении срока службы обратитесь к производителю.

**5.2** Срок хранения – 3 роки.

**5.3** Гарантийный срок эксплуатации изделия составляет 10 лет со дня продажи.

В течение гарантийного срока эксплуатации (в случае отказа изделия) производитель выполняет бесплатно ремонт изделия.

**ВНИМАНИЕ! ЕСЛИ ИЗДЕЛИЕ ЭКСПЛУАТИРОВАЛОСЬ С НАРУШЕНИЕМ ТРЕБОВАНИЙ ДАННОГО РУКОВОДСТВА ПО ЭКСПЛУАТАЦИИ, ПОКУПАТЕЛЬ ТЕРЯЕТ ПРАВО НА ГАРАНТИЙНОЕ ОБСЛУЖИВАНИЕ.**

**5.4** Гарантийное обслуживание производится по месту приобретения или производителем изделия.

**5.5** Перед отправкой на ремонт изделие должно быть упаковано в заводскую или другую упаковку, исключающую механические повреждения.

## 6 ТРАНСПОРТИРОВАНИЕ И ХРАНЕНИЕ

Изделие в упаковке производителя допускается транспортировать и хранить при температуре от минус 45 до +60 °C и относительной влажности не более 80%.
