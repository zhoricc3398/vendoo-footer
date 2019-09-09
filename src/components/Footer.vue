<template>
  <div class="footer">
    <div class="footer__content--top">
      <div class="links-group">
        <div class="links-group__column">
          <h4>ჩვენ შესახებ</h4>
          <ul>
            <li><a href="#">კარიერა</a></li>
            <li><a href="#">გუნდი</a></li>
          </ul>
        </div>
        <div class="links-group__column">
          <h4>ჩემი ანგარიში</h4>
          <ul>
            <li><a href="#">ანგარიში</a></li>
            <li><a href="#">შეკვეთები</a></li>
            <li><a href="#">ხშირად დასმული კითხვები</a></li>
            <li><a href="#">დახმარება</a></li>
          </ul>
        </div>
        <div class="links-group__column">
          <h4>დაიწყე გაყიდვა ჩვენთან</h4>
          <ul>
            <li><a href="#">უპირატესობები</a></li>
            <li><a href="#">პირობები</a></li>
            <li><a href="#">რეგისტრაცია</a></li>
          </ul>
        </div>
        <div class="links-group__column">
          <h4>პირობები</h4>
          <ul>
            <li><a href="#">გადახდის საშუალებები</a></li>
            <li><a href="#">მიტანის სერვისი</a></li>
            <li><a href="#">დაბრუნების პოლიტიკა</a></li>
            <li><a href="#">მონაცემების უსაფრთხოება</a></li>
          </ul>
        </div>
        <div class="links-group__column">
          <h4><a href="#">ბლოგი</a></h4>
          <ul>
            <li><a href="#">როგორ შევიძინოთ ტექნიკა ვენდუს საიტზე</a></li>
            <li><a href="#">როგორ შევიძინოთ ტექნიკა ვენდუს საიტზე</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
html {
  font-size: 62.5%;
}

@media screen and (max-width: 320px) {
  .footer {
    background-color: blue;
  }
}

@media screen and (min-width: 321px) and (max-width: 768px) {
  .footer {
    background-color: red;
  }
}

@media screen and (min-width: 769px) {
  .footer {
    display: flex;
    justify-content: center;

    &__content--top {
      width: 130rem;

      .links-group {
        display: flex;

        &__column {
        }
      }
    }
  }
}
</style>
