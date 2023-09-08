package exp102;
import java.awt.*;
import javax.swing.*;
import java.util.*;
public class Exp102 {
    public static void main(String[] argv)
    {
        new fmaker();
    }
}

class fmaker
{
    JTextField em,fn,ln;
    JPasswordField p,pc;
    JLabel r,r1,rl,rt;
    JPanel pn;
    JCheckBox cb;
    JFrame f;
    JButton b;
    fmaker()
    {
        f = new JFrame();
        //f.setVisible(true);
        f.setLayout(null);
        f.setSize(500,500);
        f.setTitle("Registration");
        
        JLabel t1,t2;
        t1 = new JLabel("First Name :");
        t1.setBounds(65, 90, 180, 30);
        t1.setForeground(Color.BLACK);
        t1.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        t2 = new JLabel("Last Name :");
        t2.setBounds(255, 90, 180, 30);
        t2.setForeground(Color.BLACK);
        t2.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        fn = new JTextField();
        fn.setBounds(65,115,180,30);
        fn.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        ln = new JTextField();
        ln.setBounds(255,115,180,30);
        ln.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        JLabel pm = new JLabel("Password :"),pcm = new JLabel("Re-Enter Password :");
        pm.setBounds(65, 205, 360, 30);
        pm.setForeground(Color.BLACK);
        pm.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        pcm.setBounds(65, 260, 360, 30);
        pcm.setForeground(Color.BLACK);
        pcm.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        p = new JPasswordField();
        p.setBounds(65,230,370,30);
        p.setFont(new Font("Bahnschrift", Font.PLAIN, 20));
        
        pc = new JPasswordField();
        pc.setBounds(65,285,370,30);
        pc.setFont(new Font("Bahnschrift", Font.PLAIN, 20));
        
        JLabel e = new JLabel("E-Mail :");
        e.setBounds(65, 150, 360, 30);
        e.setForeground(Color.BLACK);
        e.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        em = new JTextField();
        em.setBounds(65,175,370,30);
        em.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        r = new JLabel("--------------Register--------------");
        r.setBounds(70,20,400,40);
        r.setFont(new Font("Verdana", Font.BOLD, 20));
        
        r1 = new JLabel("Create your Account. It's Free & takes less than a Minute.");
        r1.setBounds(90, 45, 350, 40);
        r1.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        rl = new JLabel("If you Aready have an Account, then Sign-in");
        rl.setBounds(125, 385, 350, 40);
        rl.setFont(new Font("Bahnschrift", Font.PLAIN, 12));
        
        String a = ("Terms of Use");
        cb = new JCheckBox("I can Accept the given "+a+" & Privacy Policy");
        cb.setBounds(91,330,400,30);
        cb.setFont(new Font("Bahnschrift", Font.PLAIN, 12));        
        
        b = new JButton("Register Now");
        b.setBounds(90, 360, 310, 30);
        b.setFont(new Font("Bahnschrift", Font.BOLD, 15));
        b.setBackground(Color.GREEN);
        b.setForeground(Color.WHITE);
        
        f.add(b);
        f.add(r);
        f.add(cb);
        f.add(ln);
        f.add(t2);
        f.add(rl);
        f.add(p);
        f.add(t1);
        f.add(e);
        f.add(em);
        f.add(pcm);
        f.add(pm);
        f.add(pc);
        f.add(fn);
        f.add(r1);
        f.show();
        f.setDefaultCloseOperation(f.EXIT_ON_CLOSE);
    }
}
