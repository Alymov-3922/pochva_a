<template>
    <div class="wrapper">
        <nav class="navbar">
            <img class="giprozem_logo" src="/images/document/giprozem-logo.png" alt="giprozem-logo">
            <div class="title">
                <h1>Электронная выписка</h1>
                <h3>на элементарный участок</h3>
            </div>
            <div class="qr_code">
                <div id="qrcode"></div>
            </div>
        </nav>
        <div class="date_num">
            <div class="num">№ 00123</div>
            <br>
            <div class="date">Дата: 01.01.2000</div>
        </div>
        <div class="table_data">
            <table class="table table-striped table-hover">
                <thead>
                <tr>
                    <p class="table_title">Информация о земельном участке.</p>
                </tr>
                </thead>
                <hr>
                <tbody>
                <tr>
                    <th scope="row">Идентификационный номер контура (ИНК)</th>
                    <td>417-02-205-825-02-1020-1004</td>
                </tr>
                <tr>
                    <th scope="row">ЕНИ код</th>
                    <td>7-02-10-4444-1010-02-123</td>
                </tr>
                <tr>
                    <th scope="row">Место расположение:</th>
                    <td></td>

                </tr>
                <tr>
                    <td class="land_address">Адрес участка</td>
                    <td>Чуйская обл., Аламудунский район</td>
                </tr>
                <tr>
                    <td class="land_address">Долгота</td>
                    <td>78.12157110607144</td>
                </tr>
                <tr>
                    <td class="land_address">Широта</td>
                    <td>42.613751791719494</td>
                </tr>
                <tr>
                    <th scope="row">Данные о собственнике:</th>
                    <td></td>
                </tr>
                <tr>
                    <td class="owner_info">ФИО</td>
                    <td>Асанов Үсөн</td>
                </tr>
                <tr>
                    <td class="owner_info">ИНН</td>
                    <td>20101200200102</td>
                </tr>
                <tr>
                    <th scope="row">Форма собственности</th>
                    <td>Государственная собственность</td>
                </tr>
                <tr>
                    <th scope="row">Правоудостоверяющий документ</th>
                    <td>Удостоверение на право временного пользования земельным участком или договор аренды</td>
                </tr>
                <tr>
                    <th scope="row">Категория земли</th>
                    <td>Земли сельскохозяйственного назначения</td>
                </tr>
                <tr>
                    <th scope="row">Земельное угодье</th>
                    <td>Сельскохозяйственный вид угодий</td>
                </tr>
                <tr>
                    <th scope="row">Целевое назначение</th>
                    <td>Пахота</td>
                </tr>
                <tr>
                    <th scope="row">Фактическая площадь земельного участка, кв.м</th>
                    <td>28 035.26</td>
                </tr>
                <tr>
                    <th scope="row">Кадастровая стоимость, сом</th>
                    <td>100 000</td>
                </tr>
                <tr>
                    <th scope="row">Вид культуры (в текущее время)</th>
                    <td>Пшеница</td>
                </tr>
                <tr>
                    <th scope="row">Вид культуры (предшественник)</th>
                    <td>Пшеница</td>
                </tr>
                <tr>
                    <th scope="row">Урожайность (предшественник), кг</th>
                    <td>2 000</td>
                </tr>
                <tr>
                    <th scope="row">Предварительная стоимость урожая, сом</th>
                    <th>5 000 000</th>
                </tr>
                </tbody>
            </table>
        </div>
        <div class="map_content">
            <div id="map"></div>
        </div>
        <footer>
            <section class="">
                <!-- Footer -->
                <footer class="bg-secondary text-white">
                    <!-- Grid container -->
                    <div class="container p-4">
                        <!--Grid row-->
                        <div class="row">
                            <!--Grid column-->
                            <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
                                <h5 class="text-uppercase">Электронная выписка на элементарный участок</h5>

                                <p>
                                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iste atque ea quis
                                    molestias. Fugiat pariatur maxime quis culpa corporis vitae repudiandae
                                    aliquam voluptatem veniam, est atque cumque eum delectus sint!
                                </p>
                            </div>
                        </div>
                        <!--Grid row-->
                    </div>
                    <!-- Copyright -->
                    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
                        © 2022 Гипрозем
                        <a class="text-white" href="https://mdbootstrap.com/">balance.24mycrm.com</a>
                    </div>
                    <!-- Copyright -->
                </footer>
                <!-- Footer -->
            </section>
        </footer>
    </div>
</template>
