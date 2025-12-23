mvn clean test `
  -DsuitePath="artifacts" `
  -DxmlFile="testng.xml" `
  -Durl="https://opensource-demo.orangehrmlive.com/web/index.php/auth/login" `
  -Dbrowser="chrome" `
  -DtestNmaes_leave="TC_LEAVE_001_basicSearch,TC_LEAVE_004_selectLeaveStatus,TC_LEAVE_006_resetButton"
