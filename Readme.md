<!-- default file list -->
*Files to look at*:

* [FilterConfig.cs](./CS/GridViewBatchEdit/App_Start/FilterConfig.cs) (VB: [FilterConfig.vb](./VB/GridViewBatchEdit/App_Start/FilterConfig.vb))
* [RouteConfig.cs](./CS/GridViewBatchEdit/App_Start/RouteConfig.cs) (VB: [RouteConfig.vb](./VB/GridViewBatchEdit/App_Start/RouteConfig.vb))
* [WebApiConfig.cs](./CS/GridViewBatchEdit/App_Start/WebApiConfig.cs) (VB: [WebApiConfig.vb](./VB/GridViewBatchEdit/App_Start/WebApiConfig.vb))
* [HomeController.cs](./CS/GridViewBatchEdit/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/GridViewBatchEdit/Controllers/HomeController.vb))
* [Model.cs](./CS/GridViewBatchEdit/Models/Model.cs) (VB: [Model.vb](./VB/GridViewBatchEdit/Models/Model.vb))
* [_GridViewPartial.cshtml](./CS/GridViewBatchEdit/Views/Home/_GridViewPartial.cshtml)
* [EditFormEditors.cshtml](./CS/GridViewBatchEdit/Views/Home/EditFormEditors.cshtml)
* **[Index.cshtml](./CS/GridViewBatchEdit/Views/Home/Index.cshtml)**
<!-- default file list end -->
# GridView - How to implement a popup Edit Form when the Batch Edit mode is used
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t328405/)**
<!-- run online end -->


<p>This example demonstrates how to implement editing in the popup's Edit Form when the grid's Batch Edit mode is used. The main idea is to create editors for all editable fields of the grid. Then, after filling the fields, all values are set to the grid with the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebScriptsASPxClientGridViewBatchEditApi_SetCellValuetopic">ASPxClientGridView.batchEditApi.SetCellValue</a> method. </p>

<br/>


