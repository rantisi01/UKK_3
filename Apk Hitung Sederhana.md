<img width="486" height="282" alt="Screenshot 2026-02-11 105352" src="https://github.com/user-attachments/assets/a8099550-b866-49b3-8e7d-77ad8e5c950d" />
<img width="508" height="279" alt="Screenshot 2026-02-11 105403" src="https://github.com/user-attachments/assets/12aa1e7e-044c-4632-92c5-f34a056895fa" />

//Source Code Apk Hitung Sederhana
package rantisi12rpl;

public class tombol_interaktif extends javax.swing.JFrame {

    public tombol_interaktif() {
        initComponents();
         setTitle("Tombol Interaktif");
        setLocationRelativeTo(null);
    }
     

   
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jLabel1 = new javax.swing.JLabel();
        jButton1 = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        jLabel1.setText("kllik sebelum");

        jButton1.setText("klik");
        jButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton1ActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                .addContainerGap(164, Short.MAX_VALUE)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                    .addComponent(jButton1)
                    .addComponent(jLabel1))
                .addGap(160, 160, 160))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(70, 70, 70)
                .addComponent(jLabel1)
                .addGap(18, 18, 18)
                .addComponent(jButton1)
                .addContainerGap(169, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        
     
    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
         jLabel1.setText("Tombol sudah diklik!");
    }                                        

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
     java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new tombol_interaktif().setVisible(true);
            }
        });
    }
    // Variables declaration - do not modify                     
    private javax.swing.JButton jButton1;
    private javax.swing.JLabel jLabel1;
    // End of variables declaration                   
}
