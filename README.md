# hello-world

=====================

just another repository


 Dim Conn As New SqlConnection(System.Configuration.ConfigurationManager.AppSettings("ConnInfo"))
    Dim ConnNav As New SqlConnection(System.Configuration.ConfigurationManager.AppSettings("NAV_Data"))
    Dim SQLCommand As New SqlCommand
    Dim SQLNav As New SqlCommand
    Dim DataAdapter As New SqlDataAdapter
    Dim DataAdapterNav As New SqlDataAdapter
    Dim DBTable As New DataTable
