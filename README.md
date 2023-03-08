# COMPENDIODEROYECTOS
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace MenuCatalogo
{
    public partial class Principal : Form
    {
        public Principal()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            CatalogoClientes.CatalogoClientes obj = new CatalogoClientes.CatalogoClientes();
            obj.Visible = true;
            this.Visible = false;
        }

        private void button2_Click(object sender, EventArgs e)
        {
            CatalogoProductos.CatalalogoProductos obj = new CatalogoProductos.CatalalogoProductos();
            obj.Visible = true;
            this.Visible = false;
        }

        private void button3_Click(object sender, EventArgs e)
        {
            CatalogoFactura1.CatalogoFacturass obj = new CatalogoFactura1.CatalogoFacturass();
            obj.Visible = true;
            this.Visible = false;
        }

        private void button4_Click(object sender, EventArgs e)
        {
            FACTURA.FACTURASS obj = new FACTURA.FACTURASS();
            obj.Visible = true;
            this.Visible = false;
        }

        private void Principal_Load(object sender, EventArgs e)
        {

        }

        private void button5_Click(object sender, EventArgs e)
        {
            Application.Exit();
        }
    }
}
