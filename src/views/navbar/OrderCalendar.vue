<template>
  <layout>
    <template #content>
      <div class="container">
        <div class="breadcrumbs">
          パンくずリスト > <a href="">パンくずリスト</a>
        </div>
      </div>
      <main>
        <div class="order_calendar">
          <div class="calendar_header">
            <h2>
              <span class="calendar_prev">&lt;</span>
              <span class="calendar_month">2022年9月</span>
              <span class="calendar_next">&gt;</span>
            </h2>
          </div>
          <table class="calendar_table">
            <tr class="week">
              <th>月</th>
              <th>火</th>
              <th>水</th>
              <th>木</th>
              <th>金</th>
              <th>土</th>
              <th>日</th>
            </tr>

            <tr class="day">
              <td class="past_day">
                29
                <a href="">
                  <svg id="sumi" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="sumi_icon"><g><circle class="cls-2sumi" cx="14.51" cy="14.51" r="14.51"/><path class="cls-1sumi" d="m10.91,16.05c-.36,1.92-.94,3.54-1.74,4.87l-1.57-.77c.66-1.16,1.23-2.7,1.7-4.61l1.61.51Zm-.09-2.28l-1.16,1.35c-.36-.43-1.04-1.14-2.05-2.15l1.08-1.26c1.11.99,1.82,1.67,2.13,2.05Zm2.9,4.85c-.24.95-.69,1.81-1.35,2.56l-1.46-.88c.51-.65.85-1.31,1.01-1.98s.25-1.35.25-2.06v-1.24l-.87.16-.46-1.46c1.35-.18,2.5-.47,3.44-.85-.78-.54-1.44-1.18-2-1.93h-1.05v-.25l-1.15,1.29c-.41-.52-1.12-1.24-2.13-2.17l1.12-1.22c1.08.94,1.79,1.64,2.15,2.09v-1.16h3.71v-1.08h1.89v1.08h3.9v1.42h-1.2c-.53.7-1.16,1.31-1.87,1.85,1.01.33,2.22.59,3.64.78l-.59,1.56c-.35-.04-.71-.1-1.08-.16v5.96h-1.89v-2.31h-4.01Zm.27-2.23c0,.26-.01.53-.04.83h3.77v-.83h-3.73Zm0-1.77v.44h3.73v-.56c-.62-.19-1.2-.41-1.75-.66-.62.32-1.29.58-1.98.78Zm1.9-2.56c.54-.34,1.01-.71,1.42-1.12h-2.93c.44.42.94.8,1.51,1.12Z"/></g></g></svg>
                </a>
              </td>
              <td class="past_day">
                30
                <a href="">
                  <svg id="sumi" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="sumi_icon"><g><circle class="cls-2sumi" cx="14.51" cy="14.51" r="14.51"/><path class="cls-1sumi" d="m10.91,16.05c-.36,1.92-.94,3.54-1.74,4.87l-1.57-.77c.66-1.16,1.23-2.7,1.7-4.61l1.61.51Zm-.09-2.28l-1.16,1.35c-.36-.43-1.04-1.14-2.05-2.15l1.08-1.26c1.11.99,1.82,1.67,2.13,2.05Zm2.9,4.85c-.24.95-.69,1.81-1.35,2.56l-1.46-.88c.51-.65.85-1.31,1.01-1.98s.25-1.35.25-2.06v-1.24l-.87.16-.46-1.46c1.35-.18,2.5-.47,3.44-.85-.78-.54-1.44-1.18-2-1.93h-1.05v-.25l-1.15,1.29c-.41-.52-1.12-1.24-2.13-2.17l1.12-1.22c1.08.94,1.79,1.64,2.15,2.09v-1.16h3.71v-1.08h1.89v1.08h3.9v1.42h-1.2c-.53.7-1.16,1.31-1.87,1.85,1.01.33,2.22.59,3.64.78l-.59,1.56c-.35-.04-.71-.1-1.08-.16v5.96h-1.89v-2.31h-4.01Zm.27-2.23c0,.26-.01.53-.04.83h3.77v-.83h-3.73Zm0-1.77v.44h3.73v-.56c-.62-.19-1.2-.41-1.75-.66-.62.32-1.29.58-1.98.78Zm1.9-2.56c.54-.34,1.01-.71,1.42-1.12h-2.93c.44.42.94.8,1.51,1.12Z"/></g></g></svg>
                </a>
              </td>
              <td class="past_day">
                31
                <a href="">
                  <svg id="sumi" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="sumi_icon"><g><circle class="cls-2sumi" cx="14.51" cy="14.51" r="14.51"/><path class="cls-1sumi" d="m10.91,16.05c-.36,1.92-.94,3.54-1.74,4.87l-1.57-.77c.66-1.16,1.23-2.7,1.7-4.61l1.61.51Zm-.09-2.28l-1.16,1.35c-.36-.43-1.04-1.14-2.05-2.15l1.08-1.26c1.11.99,1.82,1.67,2.13,2.05Zm2.9,4.85c-.24.95-.69,1.81-1.35,2.56l-1.46-.88c.51-.65.85-1.31,1.01-1.98s.25-1.35.25-2.06v-1.24l-.87.16-.46-1.46c1.35-.18,2.5-.47,3.44-.85-.78-.54-1.44-1.18-2-1.93h-1.05v-.25l-1.15,1.29c-.41-.52-1.12-1.24-2.13-2.17l1.12-1.22c1.08.94,1.79,1.64,2.15,2.09v-1.16h3.71v-1.08h1.89v1.08h3.9v1.42h-1.2c-.53.7-1.16,1.31-1.87,1.85,1.01.33,2.22.59,3.64.78l-.59,1.56c-.35-.04-.71-.1-1.08-.16v5.96h-1.89v-2.31h-4.01Zm.27-2.23c0,.26-.01.53-.04.83h3.77v-.83h-3.73Zm0-1.77v.44h3.73v-.56c-.62-.19-1.2-.41-1.75-.66-.62.32-1.29.58-1.98.78Zm1.9-2.56c.54-.34,1.01-.71,1.42-1.12h-2.93c.44.42.94.8,1.51,1.12Z"/></g></g></svg>
                </a>
              </td>
              <td>
                1
                <a href="cart-lunch_p3.html">
                  <svg id="decision" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="decision_icon"><g><circle class="cls-2decision" cx="14.51" cy="14.51" r="14.51"/><path class="cls-1decision" d="m11.44,15.92c-.16.71-.46,1.56-.9,2.55-.44.99-.87,1.82-1.3,2.47l-1.68-.92c.46-.64.9-1.45,1.33-2.42s.71-1.71.86-2.21l1.69.53Zm-.38-2.32l-1.05,1.44c-.67-.65-1.47-1.33-2.41-2.04l.99-1.36c1.04.74,1.87,1.4,2.47,1.96Zm.62-3.07l-1.08,1.44c-.72-.67-1.54-1.38-2.46-2.11l1.06-1.32c1.18.88,2,1.54,2.48,1.99Zm4.08,6.56c-.96,1.86-2.49,3.18-4.59,3.96l-.85-1.39c1.18-.53,2.1-1.15,2.74-1.85.64-.7,1.05-1.32,1.23-1.86h-2.8v-1.54h3.11v-2.43h-2.7v-1.48h2.7v-1.55h1.89v1.55h3.43v3.92h.98v1.54h-3.83c.89,1.51,2.2,2.69,3.92,3.54l-1.16,1.44c-.79-.4-1.56-.95-2.3-1.65s-1.33-1.43-1.77-2.2Zm.73-5.11v2.43h1.63v-2.43h-1.63Z"/></g></g></svg>
                </a>
              </td>
              <td>
                2
                <a href="cart-lunch_p3.html">
                  <svg id="decision" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="decision_icon"><g><circle class="cls-2decision" cx="14.51" cy="14.51" r="14.51"/><path class="cls-1decision" d="m11.44,15.92c-.16.71-.46,1.56-.9,2.55-.44.99-.87,1.82-1.3,2.47l-1.68-.92c.46-.64.9-1.45,1.33-2.42s.71-1.71.86-2.21l1.69.53Zm-.38-2.32l-1.05,1.44c-.67-.65-1.47-1.33-2.41-2.04l.99-1.36c1.04.74,1.87,1.4,2.47,1.96Zm.62-3.07l-1.08,1.44c-.72-.67-1.54-1.38-2.46-2.11l1.06-1.32c1.18.88,2,1.54,2.48,1.99Zm4.08,6.56c-.96,1.86-2.49,3.18-4.59,3.96l-.85-1.39c1.18-.53,2.1-1.15,2.74-1.85.64-.7,1.05-1.32,1.23-1.86h-2.8v-1.54h3.11v-2.43h-2.7v-1.48h2.7v-1.55h1.89v1.55h3.43v3.92h.98v1.54h-3.83c.89,1.51,2.2,2.69,3.92,3.54l-1.16,1.44c-.79-.4-1.56-.95-2.3-1.65s-1.33-1.43-1.77-2.2Zm.73-5.11v2.43h1.63v-2.43h-1.63Z"/></g></g></svg>
                </a>
              </td>
              <td>3</td>
              <td>4</td>
            </tr>
            
            <tr class="day">
              <td>
                5
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                6
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                7
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                8
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                9
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>10</td>
              <td>11</td>
            </tr>
            
            <tr class="day">
              <td>
                12
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                13
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                14
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                15
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                16
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>17</td>
              <td>18</td>
            </tr>
            
            <tr class="day">
              <td>
                19
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                20
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                21
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                22
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                23
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>24</td>
              <td>25</td>
            </tr>
            
            <tr class="day">
              <td>
                26
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                27
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                28
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                29
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>
                30
                <a href="cart-lunch_p3.html">
                  <svg id="circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.03 29.03"><defs></defs><g id="circle_icon"><g><path class="cls-1circle" d="m14.51,28.03C7.06,28.03,1,21.97,1,14.52S7.06,1,14.51,1s13.51,6.06,13.51,13.51-6.06,13.51-13.51,13.51Z"/><path class="cls-2circle" d="m14.51,2c6.9,0,12.52,5.61,12.52,12.52s-5.61,12.52-12.52,12.52S2,21.42,2,14.52,7.61,2,14.51,2m0-2C6.5,0,0,6.5,0,14.52s6.5,14.52,14.51,14.52,14.52-6.5,14.52-14.52S22.53,0,14.51,0h0Z"/></g></g></svg>
                </a>
              </td>
              <td>31</td>
              <td>1</td>
            </tr>
            
          </table>

          <div class="calendar_result">
            <div class="flex_wrap align_center">

              <div class="month_order_total font_16">
                <p>
                  本日の合計
                  <span class="total_num">1個</span>
                  <span class="total_price">400円</span>
                </p>
                <p>
                  当月の合計
                  <span class="total_num">2個</span>
                  <span class="total_price">800円</span>
                </p>
              </div>

              <div class="order_day">
                <p class="order_day_single">
                  <a href="cart-lunch_p2_2.html">
                    複数日選択する
                  </a>
                </p>
              </div>

            </div>
          </div>

        </div>

        <div class="calendar_info">
          <p>
            ご注文期限：当日９：００まで
          </p>
          <ul>
            <li>各種注釈をここにテキスト反映します。</li>
            <li>毎週〇曜日のメニューは日替りメニューとなります。詳しくはスタッフまでご確認ください。</li>
            <li>容器回収は、原則次回お届け日の回収となります。</li>
          </ul>
        </div>

      </main>
    </template>
  </layout>
</template>

<script setup>
import layout from '../layout/App.vue'
</script>

<style scoped>
.cls-1sumi{fill:#fff;}.cls-2sumi{fill:#666;}
.cls-1decision{fill:#fff;}.cls-2decision{fill:#f17225;}
.cls-1circle{fill:#fff;}.cls-2circle{fill:#f17225;}
</style>