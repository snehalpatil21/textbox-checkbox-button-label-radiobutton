# textbox-checkbox-button-label-radiobutton
 
using System;
using System.Windows.Forms;

namespace studinfo
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btn1_Click(object sender, EventArgs e)
        {
            lblname.Text=txt1.Text;
            if(chk1.Checked==true)
            {
                lblhobb.Text=chk1.Text;
            }
            if(chk2.Checked==true)
              {
                lblhobb.Text=chk2.Text;
              }
            if (rdb1.Checked == true)
            {
                lblgend.Text = rdb1.Text;
            }
            if (rdb2.Checked == true)
            {
                lblgend.Text = rdb2.Text;
            }    
        } } } 
}   

    1

					
