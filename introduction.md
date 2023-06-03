import javax.swing.JOptionPane;
public class PerkenalanDiri {
    public static void main(String[] args) {

        String nama = JOptionPane.showInputDialog("Masukkan Nama Anda:");
        
        String umurStr = JOptionPane.showInputDialog("Masukkan Umur Anda:");
        int umur = Integer.parseInt(umurStr);
        
        String hobi = JOptionPane.showInputDialog("Masukkan Hobi Anda:");
        
        String perkenalan = "Nama: " + nama + "\nUmur: " + umur + " tahun\nHobi: " + hobi;
        
        JOptionPane.showMessageDialog(null, perkenalan, "Perkenalan Diri", JOptionPane.INFORMATION_MESSAGE);
    }
}
