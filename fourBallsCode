import processing.core.PApplet;
public class FourBallsP extends PApplet{

    public static final int WIDTH = 800;
    public static final int HEIGHT = 600;
    public static final int DIAMETER = 10;
    int x1 = 0,x2=0,x3=0,x4=0;
    int h4 = (4 * HEIGHT) / 5;
    int h3 = (3 * HEIGHT) / 5;
    int h2 = (2*HEIGHT)/5;
    int h1 = HEIGHT/5;

    public static void main(String[] args) {
        PApplet.main("FourBallsP",args);
    }

    @Override
    public void settings() {
        size(WIDTH, HEIGHT);
    }

    @Override
    public void setup() {
        fill(color(random(255),random(255),random(255)));
        stroke(color(random(255),random(255),random(255)));
    }

    @Override
    public void draw() {
        drawBall1();
        drawBall2();
        drawBall3();
        drawBall4();
    }

    private void drawBall4() {
        ellipse(x4, h4, DIAMETER,DIAMETER);
        x4+=4;
    }

    private void drawBall3() {
        ellipse(x3, h3, DIAMETER,DIAMETER);
        x3+=3;
    }

    private void drawBall2() {
        ellipse(x2,h2, DIAMETER,DIAMETER);
        x2+=2;
    }

    private void drawBall1() {
        ellipse(x1,h1, DIAMETER,DIAMETER);
        x1++;
    }
}
