# Html-Table-Structure-Info


 <table>
   
  <tr>
    <th>Col_1</th>
    <th>Col_2</th>
  </tr>
  
  <tr>
    <td>Data_1</td>
    <td>Data_2</td>
  </tr>
  
  <tr>
    <td>Data</td>
    <td>Data</td>
  </tr>
  
</table> 

# th are heading , td is simple data , bootstrap has 12 cols , so we use them to expant cells



## ----------- Odoo Table ----------


<table class="table table-sm table-bordered" width="100%">
                            <thead>
                                <tr>
                                    <th colspan="12"><h2 style=" color:#50a3ff;">Borrower Details</h2></th>
                                </tr>
                            </thead>
 
                            <tbody>
                                <tr>
                                    <th colspan="2">Employee</th>   # ab 12 thi total width humne sab ko 2 ,2 de kr pori krde, agr zyada krte to itne head na bnte phr, ye sub heads han 
                                    <th colspan="2">Age</th>
                                    <th colspan="2">Department</th>
                                    <th colspan="2">Job Designation</th>
                                    <th colspan="2">Currency</th>
                                    <th colspan="2">Payable Interest</th>
                                </tr>
                            </tbody>

                            <tr>
                                <td colspan="2" style="text-align: center;">
                                    <span t-field="obj.employee_id.name"/>
                                </td>
                                <td colspan="2" style="text-align: center;">
                                    <span t-field="obj.emp_age"/>
                                </td>
                                <td colspan="2" style="text-align: center;">
                                    <span t-field="obj.dep_id.name"/>
                                </td>
                                <td colspan="2" style="text-align: center;">
                                    <span t-field="obj.employee_job.name"/>
                                </td>
                                <td colspan="2" style="text-align: center;">
                                    <span t-field="obj.currency"/>
                                </td>
                                <td colspan="2" style="text-align: center;">
                                    <span t-field="obj.intrest"/>
                                </td>
                            </tr>

                        </table>































 
