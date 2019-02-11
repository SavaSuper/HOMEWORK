import java.awt.event.*;

public class GrLibrary extends Frame implements WindowListener {

    public void windowOpened(WindowEvent e) {};

    public void windowClosing(WindowEvent e) {
        dispose();
        System.exit(0);
    };

    public void windowClosed(WindowEvent e) {};
    public void windowIconified(WindowEvent e) {};
    public void windowDeiconified(WindowEvent e) {};
    public void windowActivated(WindowEvent e) {};
    public void windowDeactivated(WindowEvent e) {};

    public void paint(Graphics g) {

        Dimension rc = getSize();
        Insets in = getInsets();

        int RH = rc.width;
        int RW = rc.height;

        int minX = in.left;
        int maxX = RH - in.right;
        int minY = in.top;
        int maxY = RW - in.bottom;
        int x1, y1, x2, y2;
        int cr,cq,cb;
        int d;
        int cx, cy, dx, dy;
        float wdk=3.0f;

        cx = Math.abs(maxX - minX) / 2;
        cy = Math.abs(maxY - minY) / 2;
        dx = maxX / 10;
        dy = maxY / 10;

        g.setColor(new Color(0x8F46C8));
        String txt = "Програмування графічними примітивами: ";
        g.setFont(new Font("Trebuchet Ms", Font.PLAIN, 24));
        int nf = g.getFontMetrics().stringWidth(txt);
        g.drawString(txt, nf / 2 - 220, nf / 2 - 180);

        Graphics2D g2 = (Graphics2D) g;
        g2.setStroke(new BasicStroke(wdk));


        // TO DO
        wdk=3f;
        g2.setStroke(new BasicStroke(wdk));
        g.setColor(new Color(0x000000));

        x1=100;
        y1=120;
        x2=x1+200;
        y2=y1;

        g.drawLine(x1,y1,x2,y2);
        g.drawLine(x1,y1,x2-200,y2+250);
        g.drawLine(x1,y1+250,x2-180,y2+320);
        g.drawLine(x1+20,y1+320,x2-20,y2+320);
        g.drawLine(x1+180,y1+320,x2,y2+250);
        g.drawLine(x1+200,y1+250,x2,y2+230);
        g.drawArc(x2-73,y2+20,150,210,90,-180);
        g.drawLine(x2,y2,x2,y2+20);
        g.drawLine(x2,y2+65,x2,y2+189);
        g.drawArc(x2-35,y2+65,75,124,90,-180);

        wdk=2f;
        g2.setStroke(new BasicStroke(wdk));
        g.setColor(new Color(0x000000));

        g.drawLine(x1,y1,x1,y2-40);
        g.drawLine(x1,y1,x1-40,y2);
        g.drawLine(x1,y1+250,x1-40,y2+250);
        g.drawLine(x2,y2,x2,y2-40);
        g.drawLine(x2,y2+20,x2+200,y2+20);
        g.drawLine(x2,y1+230,x2+200,y2+230);
        g.drawLine(x1+200,y1+250,x2+30,y2+250);
        g.drawLine(x1+180,y1+320,x2+30,y2+320);
        g.drawLine(x1+180,y1+320,x1+180,y2+360);
        g.drawLine(x1+20,y1+320,x1+20,y2+360);
        g.drawLine(x2,y1+124,x2+40,y2+124);
        g.drawLine(x1,y1-20,x2,y2-20);
        g.drawLine(x2+140,y1+20,x2+140,y2+230);
        g.drawLine(x2+20,y1+250,x2+20,y2+320);
        g.drawLine(x1+180,y1+350,x1+20,y2+350);
        g.drawLine(x1-20,y1,x1-20,y1+250);

        g.drawString("a", 192, 494);
        g.drawString("b", 197, 94);
        g.drawString("d", 445, 250);
        g.drawString("e", 60, 250);
        g.drawString("c", 312, 237);
        g.drawString("c", 328, 410);
        g.drawString(", де",550,94);
        g.drawString("a=6;",555,124);
        g.drawString("b=8;",555,154);
        g.drawString("c=2;",555,184);
        g.drawString("d=8;",555,214);
        g.drawString("e=10;",555,244);


    }

    public GrLibrary() {
        super("Графічні примітиви.");
        addWindowListener(this);
        setLayout(null);
        setLocation(120,100);
        setSize(800,600);
        show();
    }
}
