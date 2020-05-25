# IAMApprovalsViaEmail
#EmailLookupService.zip -
 >It contaoins source code of email lookup programm which will read emails and invoke ws calls to approve the request.
 >This programm can be scheduled to run after verey 1 hour to read emails and take action.
 > Depends on jar 
 1.ews-java-api-2.0.jar
 2.httpclient-4.5.12.jar
 3.commons-logging-1.2.jar
 4.httpcore-4.4.13.jar
 5.commons-codec-1.14.jar
 6.commons-lang3-3.10.jar
 7.joda-time-2.10.6.jar
 8.IAMApprovalService.jar
 
 IAMApprovalService.zip- 
 >It is WS client to invoke isim extension ws
 Dependent on jar itim_ws_client.jar, itim_ws_model.jar
 
 HandleIAMApprovals.zip - 
 >This is extension webservice.This needs to be registered in isim/data/wsextension.properties file.
 >jar of this project needs to copy in isim/lib and ITIM.ear folder and also needs to be added in ISIM WAS classpath
 
 
 
