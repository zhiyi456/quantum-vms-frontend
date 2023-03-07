<template>
<!-- Latest compiled and minified CSS -->

<div>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <SideBarVendor></SideBarVendor>
    <div class="main">
        <div class="mx-4">
            <div>   
                <div class="row">
                    <h1>Account Manager</h1>
                </div>
                <div class="row">
                    <p class="col">Overview of vendor accounts</p> 
                    <div class="col">
                        <button type="button" class="btn btn-dark float-end">Create</button>
                    </div>
                </div>
                    

            </div>
        

            <table class="table table-hover">
                <thead>
                    <tr>
                    <th scope="col">ID</th>
                    <th scope="col">Name</th>
                    <th scope="col">Email</th>
                    <th scope="col">Contact No</th>
                    <th scope="col">Date Created</th>
                    <th scope="col">Actions</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                    <th scope="row">1</th>
                    <td>Mark</td>
                    <td>Otto</td>
                    <td>@mdo</td>
                    <td>@mdo</td>
                    <td>@mdo</td>
                    </tr>
                    <tr>
                    <th scope="row">2</th>
                    <td>Jacob</td>
                    <td>Thornton</td>
                    <td>@fat</td>
                    <td>@mdo</td>
                    <td>@mdo</td>
                    </tr>
                    <tr>
                    <th scope="row">3</th>
                    <td>Larry the Bird</td>
                    <td>@twitter</td>
                    <td>@mdo</td>
                    <td>@mdo</td>
                    <td>@mdo</td>
                    </tr>
                </tbody>
            </table>
        </div>
        
    </div>
</div>
</template>

<script>
import SideBarVendor from './side-bar-vendor'

export default {
  name: 'AccManager',
  metaInfo: {
    title: 'Account-Manager - Quantum VMS',
    meta: [
      {
        property: 'og:title',
        content: 'Account-Manager - Quantum VMS',
      },
    ],
  },
  components: {
    SideBarVendor 
  }
}
</script>

<style>

.main {
  margin-left: 240px; /* Same as the width of the sidenav */
  padding: 0px 10px;
}


.account-manager-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}

.account-manager-account-manager {
  width: 100%;
  height: 1080px;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: transparent;
  background-color: rgba(246, 249, 255, 1);
}

.account-manager-frame6 {
  top: 53px;
  left: 308px;
  width: 1512px;
  display: flex;
  position: absolute;
  align-items: flex-start;
  border-color: transparent;
  flex-direction: column;
}
.account-manager-frame8 {
  display: flex;
  position: relative;
  align-items: flex-start;
  border-color: transparent;
  margin-bottom: 32px;
  flex-direction: column;
}
.account-manager-frame9 {
  display: flex;
  position: relative;
  align-items: flex-start;
  border-color: transparent;
  flex-direction: column;
}
.account-manager-frame5 {
  width: 1512px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: transparent;
  justify-content: space-between;
}
.account-manager-frame20 {
  display: flex;
  position: relative;
  align-items: flex-start;
  border-color: transparent;
  flex-direction: column;
}
.account-manager-text12 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 28px;
  align-self: auto;
  font-style: Medium;
  text-align: left;
  font-family: Inter;
  font-weight: 500;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 4px;
  text-decoration: none;
}
.account-manager-text14 {
  color: rgba(125, 131, 152, 1);
  height: auto;
  font-size: 16px;
  align-self: auto;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame11 {
  display: flex;
  position: relative;
  align-items: flex-start;
  border-color: transparent;
}
.account-manager-frame21 {
  display: flex;
  padding: 10px 20px;
  position: relative;
  box-shadow: 0px 3px 6px 0px rgba(18, 18, 18, 0.029999999329447746) ;
  align-items: flex-start;
  border-color: rgba(125, 131, 151, 0.30000001192092896);
  border-style: solid;
  border-width: 1px;
  border-radius: 6px;
  background-color: rgba(18, 18, 18, 1);
}
.account-manager-frame1 {
  display: flex;
  position: relative;
  align-items: center;
  border-color: transparent;
}
.account-manager-vector4 {
  width: 14px;
  height: 14px;
  position: relative;
  margin-right: 12px;
}
.account-manager-text16 {
  color: rgba(255, 255, 255, 1);
  height: auto;
  font-size: 16px;
  align-self: auto;
  font-style: Bold;
  text-align: left;
  font-family: Inter;
  font-weight: 700;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame4 {
  width: 1512px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: transparent;
  flex-direction: column;
}
.account-manager-frame17 {
  display: flex;
  padding: 24px;
  position: relative;
  align-self: stretch;
  align-items: flex-start;
  border-color: rgba(85, 86, 90, 0.11999999731779099);
  border-style: solid;
  border-width: 1px;
  border-radius: 8px 8px 0 0;
  margin-bottom: 0px;
  flex-direction: column;
  background-color: rgba(252, 252, 252, 1);
}
.account-manager-group3 {
  width: 1382px;
  height: 22px;
  display: flex;
  padding: 0;
  position: relative;
  align-self: auto;
  box-sizing: border-box;
  align-items: flex-start;
  flex-shrink: 1;
  border-color: transparent;
  border-style: none;
  border-width: 0;
  margin-right: 0;
  border-radius: 0px 0px 0px 0px;
  margin-bottom: 0;
  flex-direction: row;
  justify-content: flex-start;
  background-color: transparent;
}
.account-manager-frame18 {
  top: 1px;
  left: 0px;
  width: 129.41177368164062px;
  display: flex;
  position: absolute;
  align-items: center;
  flex-shrink: 0;
  border-color: transparent;
}
.account-manager-frame81 {
  display: flex;
  position: relative;
  align-items: center;
  border-color: transparent;
}
.account-manager-text18 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Medium;
  text-align: left;
  font-family: Inter;
  font-weight: 500;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame91 {
  top: 0px;
  left: 316px;
  display: flex;
  position: absolute;
  align-items: center;
  border-color: transparent;
}
.account-manager-text20 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Medium;
  text-align: left;
  font-family: Inter;
  font-weight: 500;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame92 {
  top: 0px;
  left: 576px;
  display: flex;
  position: absolute;
  align-items: center;
  border-color: transparent;
}
.account-manager-text22 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Medium;
  text-align: left;
  font-family: Inter;
  font-weight: 500;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame93 {
  top: 0px;
  left: 832px;
  display: flex;
  position: absolute;
  align-items: center;
  border-color: transparent;
}
.account-manager-text24 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Medium;
  text-align: left;
  font-family: Inter;
  font-weight: 500;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame94 {
  top: 0px;
  left: 1051px;
  display: flex;
  position: absolute;
  align-items: center;
  border-color: transparent;
}
.account-manager-text26 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Medium;
  text-align: left;
  font-family: Inter;
  font-weight: 500;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame95 {
  top: 0px;
  left: 1331px;
  display: flex;
  position: absolute;
  align-items: center;
  border-color: transparent;
}
.account-manager-text28 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Medium;
  text-align: left;
  font-family: Inter;
  font-weight: 500;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame3 {
  display: flex;
  position: relative;
  align-self: stretch;
  align-items: flex-start;
  border-color: transparent;
  flex-direction: column;
}
.account-manager-frame10 {
  width: 1512px;
  height: 92px;
  display: flex;
  padding: 24px;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: rgba(85, 86, 90, 0.11999999731779099);
  border-style: solid;
  border-width: Symbol(figma.mixed)px;
  margin-bottom: 0px;
  background-color: rgba(255, 255, 255, 1);
}
.account-manager-text30 {
  top: 32px;
  left: 340px;
  color: rgba(125, 131, 152, 1);
  width: 38px;
  height: auto;
  position: absolute;
  font-size: 14px;
  align-self: auto;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame101 {
  top: 33px;
  left: 25px;
  width: 7px;
  display: flex;
  position: absolute;
  align-items: center;
  border-color: transparent;
}
.account-manager-frame7 {
  width: 7px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: transparent;
  flex-direction: column;
}
.account-manager-text32 {
  color: rgba(125, 131, 152, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-text33 {
  top: 32px;
  left: 600px;
  color: rgba(125, 131, 152, 1);
  width: 147px;
  height: auto;
  position: absolute;
  font-size: 14px;
  align-self: auto;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-text35 {
  top: 33px;
  left: 850px;
  color: rgba(125, 131, 152, 1);
  height: auto;
  position: absolute;
  font-size: 14px;
  align-self: auto;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-text37 {
  top: 28px;
  left: 1075px;
  color: rgba(125, 131, 152, 1);
  height: auto;
  position: absolute;
  font-size: 14px;
  align-self: auto;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame102 {
  top: 22px;
  left: 1317px;
  width: 68px;
  display: flex;
  padding: 8px 12px;
  position: absolute;
  box-shadow: 0px 3px 6px 0px rgba(18, 18, 18, 0.029999999329447746) ;
  align-items: flex-start;
  border-color: rgba(125, 131, 151, 0.30000001192092896);
  border-style: solid;
  border-width: 1px;
  border-radius: 6px;
  background-color: rgba(255, 255, 255, 1);
}
.account-manager-frame11 {
  display: flex;
  position: relative;
  align-items: center;
  border-color: transparent;
}
.account-manager-vector5 {
  width: 15px;
  height: 15px;
  position: relative;
  margin-right: 4px;
}
.account-manager-text39 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Thin;
  text-align: left;
  font-family: Inter;
  font-weight: 100;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-frame111 {
  top: 23px;
  left: 1390px;
  width: 84px;
  display: flex;
  padding: 8px 12px;
  position: absolute;
  box-shadow: 0px 3px 6px 0px rgba(18, 18, 18, 0.029999999329447746) ;
  align-items: flex-start;
  border-color: rgba(125, 131, 151, 0.30000001192092896);
  border-style: solid;
  border-width: 1px;
  border-radius: 6px;
  background-color: rgba(255, 255, 255, 1);
}
.account-manager-frame12 {
  display: flex;
  position: relative;
  align-items: center;
  border-color: transparent;
}
.account-manager-vector6 {
  width: 13px;
  height: 15px;
  position: relative;
  margin-right: 4px;
}
.account-manager-text41 {
  color: rgba(18, 18, 18, 1);
  height: auto;
  font-size: 14px;
  align-self: auto;
  font-style: Thin;
  text-align: left;
  font-family: Inter;
  font-weight: 100;
  line-height: 150%;
  font-stretch: normal;
  margin-right: 0;
  margin-bottom: 0;
  text-decoration: none;
}
.account-manager-materialsymbolsdeleteforeverrounded {
  top: 6px;
  left: 1407px;
  width: 20px;
  height: 20px;
  display: flex;
  overflow: hidden;
  position: absolute;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: transparent;
}
.account-manager-frame15 {
  display: flex;
  padding: 24px;
  position: relative;
  align-self: stretch;
  align-items: flex-start;
  border-color: rgba(85, 86, 90, 0.11999999731779099);
  border-style: solid;
  border-width: Symbol(figma.mixed)px;
  margin-bottom: 0px;
  flex-direction: column;
  background-color: rgba(255, 255, 255, 1);
}
.account-manager-frame16 {
  display: flex;
  padding: 24px;
  position: relative;
  align-self: stretch;
  align-items: flex-start;
  border-color: rgba(85, 86, 90, 0.11999999731779099);
  border-style: solid;
  border-width: Symbol(figma.mixed)px;
  flex-direction: column;
  background-color: rgba(252, 252, 252, 1);
}

</style>