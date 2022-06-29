<template>
  <div>
    <!-- PC -->
    <div class="menu-main-pc gt-md row justify-between">
      <div class="row">
        <div class="logo-pc">
          <img src="../../public/logo.svg" alt="" />
        </div>
        <div class="selectPage">หน้าหลัก</div>
        <div class="menuPage">เกมทั้งหมด</div>
        <div class="menuPage">โปรโมชั่น</div>
        <div class="menuPage">บทความ</div>
        <div class="menuPage">ติดต่อเรา</div>
      </div>
      <div class="profilePic">
        <img src="../../public/profile.svg" alt="" />
      </div>
    </div>

    <!-- Tablet -->
    <div class="gt-xs lt-lg menu-main-tablet font14 row justify-between">
      <div class="row">
        <div class="logo-tablet">
          <img src="../../public/logo.svg" alt="" height="45px" />
        </div>
        <div class="selectPage-t">หน้าหลัก</div>
        <div class="menuPage-t">เกมทั้งหมด</div>
        <div class="menuPage-t">โปรโมชั่น</div>
        <div class="menuPage-t">บทความ</div>
        <div class="menuPage-t">ติดต่อเรา</div>
      </div>
      <div class="profilePic-t">
        <img src="../../public/profile.svg" height="30px" alt="" />
      </div>
    </div>

    <!-- Mobile -->
    <div class="lt-sm menu-main-m">
      <div class="row justify-between">
        <!-- <div class="menu-m" @click="drawer != drawer">
          <q-icon name="fa-solid fa-bars" />
        </div> -->
        <div class="logo-m">
          <img src="../../public/logo.svg" alt="" height="40px" />
        </div>

        <div class="profilePic-m">
          <img src="../../public/profile.svg" height="30px" alt="" />
        </div>
      </div>
      <div class="menu-mobile">
        <div class="row">
          <div style="width: 20%" align="center">
            <div style="padding-top: 10px">
              <img src="../../public/m1.svg" alt="" />
            </div>
            <div class="titleMenu">หน้าหลัก</div>
          </div>
          <div style="width: 20%" align="center">
            <div style="padding-top: 14px">
              <img src="../../public/m2.svg" alt="" />
            </div>
            <div class="titleMenu">เกม</div>
          </div>
          <div style="width: 20%" align="center">
            <div style="padding-top: 12px">
              <img src="../../public/m3.svg" alt="" />
            </div>
            <div class="titleMenu">โปรโมชั่น</div>
          </div>
          <div style="width: 20%" align="center">
            <div style="padding-top: 14px">
              <img src="../../public/m4.svg" alt="" />
            </div>
            <div class="titleMenu">บทความ</div>
          </div>
          <div style="width: 20%" align="center">
            <div style="padding-top: 11px">
              <img src="../../public/m5.svg" alt="" />
            </div>
            <div class="titleMenu">ติดต่อเรา</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      drawer: false,
    };
  },
};
</script>

<style lang="scss" scoped>
.menu-main-pc {
  max-width: 1400px;
  width: 100%;
  background-color: #091f33;
  color: #ffffff;
  height: 80px;
  margin: auto;
}
.logo-pc {
  padding-top: 18px;
  padding-left: 25px;
  padding-right: 25px;
  cursor: pointer;
}
.selectPage {
  width: 150px;
  line-height: 80px;
  text-align: center;
  background-color: #ffcb11;
  color: #091f33;
}
.menuPage {
  width: 150px;
  line-height: 80px;
  text-align: center;
  cursor: pointer;
}
.menuPage:hover {
  color: #ffcb11;
}
.profilePic {
  padding-top: 15px;
  padding-right: 15px;
  cursor: pointer;
}

.menu-main-tablet {
  width: 100%;
  height: 55px;
  background-color: #091f33;
  color: #ffffff;
}
.logo-tablet {
  padding-top: 10px;
  padding-left: 15px;
  padding-right: 15px;
}
.menuPage-t {
  width: 100px;
  line-height: 55px;
  text-align: center;
  cursor: pointer;
}
.selectPage-t {
  width: 100px;
  height: 55px;
  line-height: 55px;
  text-align: center;
  background-color: #ffcb11;
  color: #091f33;
}
.profilePic-t {
  padding-top: 12px;
  padding-right: 8px;
}
.menu-main-m {
  width: 100%;
  height: 45px;
  background-color: #091f33;
  color: #ffffff;
}
.menu-m {
  padding-top: 8px;
  padding-left: 10px;
  padding-right: 10px;
}
.logo-m {
  padding-left: 10px;
  padding-top: 5px;
}
.profilePic-m {
  padding-top: 8px;
  padding-right: 5px;
}
.menu-mobile {
  width: 100%;
  height: 64px;
  background-color: #091f33;
  border-radius: 10px 10px 0px 0px;
  position: fixed;
  bottom: 0px;
}
.titleMenu {
  font-size: 12px;
}
</style>
